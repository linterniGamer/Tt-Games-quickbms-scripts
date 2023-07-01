# Tt Games - quickbms scripts

## :bangbang: Disclaimer
This repository was made just with the intention of preserve the script versions I use while modding games made by Tt games. This might either be used to extract the content inside the DAT files of the game or for a different purpose.

All credit goes to quickbms creators cause I didn't make any of these scripts or the quickbms tool.

##
If I had to update anything from this repository, let me know here or on Discord: linternigamer

Tt Games Modding Discord invitation link: [![Discord](https://img.shields.io/badge/Discord-Invite-7289DA.svg?logo=Discord&style=flat-square)](https://discord.gg/9gYXPka)

My Discord server: [![Discord](https://img.shields.io/badge/Discord-Invite-7289DA.svg?logo=Discord&style=flat-square)](https://discord.gg/RrvzDAC)

## :floppy_disk: $\color{#00CC00} \mathtt{\textbf{\large{How to download the files of this repository}}}$
Just simply click the green box with the word that says "Code" and then it will open a small window. On that window, select the option "Download ZIP". It will download all the files in your PC. When the process is done, go to where the ZIP file was downloaded and extract its content there. After that you are free to use the tool 😉.

## :ballot_box_with_check: $\color{#0055FF} \mathtt{\textbf{\large{How to use quickbms to extract the DAT files}}}$
RogerRoger tutorial about it: https://www.youtube.com/watch?v=_EQ3hPrh0V8

Tutorial I made to start modding TCS: https://www.youtube.com/watch?v=gchonYfKs04&t=2s

## :warning: Problems reported: $\color{#FF0000} \mathtt{\textbf{\large{4}}}$
### $\color{#FF5500} \mathtt{\textbf{\large{1.-}}}$ Why the tool isn't working after double clicking it?
In case that happened, then do the following:

1.- In the tab above, go to File -> Open Windows Powershell.

2.- Put the name of the file you wanna open with its extension.

3.- Follow the steps to be able to extract dat files.

### $\color{#FF5500} \mathtt{\textbf{\large{2.-}}}$ Why the tool doesn't extract the files contained inside the DAT files?
It might be due to these reasons:

1.- The bms script you selected is not the correct one.

2.- The DAT file is not a valid one (E.g. Transformers The Game for Xbox 360).

3.- The DAT files are corrupted (careful with extracting DAT files from PS3 or Xbox 360 ISOs).

4.- The DAT file is too big to be processed on the memory, showing memory allocation problem on quickbms (happens with the DAT file from TCS PS3).

### $\color{#FF5500} \mathtt{\textbf{\large{3.-}}}$ I opened the DAT files with another program and they're not DAT files anymore. What can I do now?
The DAT files have not been altered, just your computer shows them with a different icon. What you need to check to make sure they are still DAT files is the type of file they are. If it says `DAT file` then it keeps being a DAT file and so it can be extracted easily with quickbms following the correct steps.

If they aren't DAT files anymore, get the original DAT files and DO NOT try to open them again with a different program.

### $\color{#FF5500} \mathtt{\textbf{\large{4.-}}}$ When I open quickbms, it closes and even when I make it stay open, it says something different and the second tab doesn't open. What I would do?
Run it as administrator and done.

### $\color{#FF5500} \mathtt{\textbf{\large{5.-}}}$ How can I extract the files that are inside a console version of the game?
It depends of which console version of the game we're talking about:
- $\color{#FF8800} \mathtt{\textbf{\large{Android and IOS}}}$: the game files are all contained in the `.obb` file, so extract it using quickbms like it was a DAT file.
- $\color{#FF8800} \mathtt{\textbf{\large{Xbox 360}}}$: sometimes the game comes compressed on an ISO file and we can see it contains 2 folder called `AUDIO_TS` and `VIDEO_TS`. In that case you need a tool that has been built specifically to extract Xbox 360 ISO files like **XBOX 360 ISO Extract**. By opening the tool and selecting the ISO of the game you wanna decompress, it will extract all the content from it and everything will look normal now (there would be the case in which there are no DAT files and everything is extracted, so $\color{#0066FF} \mathtt{\textbf{\large{say thanks to the devs}}}$ :innocent:).
- $\color{#FF8800} \mathtt{\textbf{\large{Wii}}}$: sometimes the game comes compressed on a `.wbfs` file or `.nkit.iso` file. Depending of which of them you have to deal with you will need:
  - **Nkit**: to extract the `.nkit.iso` file or convert it to an iso file you can extract later.
  - **Wbfs to ISO**: to convert the `.wbfs` file to an iso file you can later extract using Nkit.
  SInce here just follow the steps (there would be the case **again** in which there are no DAT files and everything is extracted, so $\color{#0066FF} \mathtt{\textbf{\large{say thanks again to the devs}}}$ :innocent:).
- $\color{#FF8800} \mathtt{\textbf{\large{PS3}}}$: the files are all contained in a `.pkg` file, so using **PSN PKG Decryptor & Extractor** should convert it to iso. From there just extract the files of the iso normally. If there were no DAT files and some weird files ended on 60000 or something like that, **those files are a fragmented DAT file** you will need to join using a hex editor to be able to extract the content inside of it.
- $\color{#FF8800} \mathtt{\textbf{\large{PSP}}}$: Use UMGDen to extract the files. A good example of having issues here with DAT files is **Transformers: The Game** on this console version. **There are no DAT files** and the files contained inside of it contain unknown extensions that make us $\color{#FF0000} \mathtt{\textbf{\large{unavailable to extract them}}}$.
