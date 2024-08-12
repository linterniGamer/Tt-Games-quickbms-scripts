<h1><p align="center"><b>Tt Games - quickbms scripts</b></p></h1>

# 📑 Index
- [❗ Disclaimer](#-disclaimer)
- [💾 Download](#-how-to-download-the-files-of-this-repository)
- [☑️ Quickbms Usage](#️-how-to-use-quickbms)
- [⚠️ Problems reported (6)](#️-problems-reported)

# ❗ Disclaimer
This repository has been made just with the intention of preserve the script versions I use while modding games made by Tt games. This might either be used to extract the content inside the DAT files of the game or for a different purpose.

$\color{#0055FF} \mathtt{\textbf{All credit goes to quickbms developers cause I didn't make any of these scripts or the quickbms tool.}}$

##
If I had to update anything from this repository, please let me know here or on Discord: linternigamer

[![Discord](https://img.shields.io/badge/TT%20Games%20Modding%20Discord-Invitation%20link-7289DA.svg?logo=Discord&style=flat-circle&labelColor=04192E&color=003EAB&logoColor=1FDDC9)](https://discord.gg/9gYXPka)

[![Discord](https://img.shields.io/badge/linterni%20Gamer's%20Discord%20Server-Invitation%20link-7289DA.svg?logo=Discord&style=flat-circle&logoColor=0051FF&labelColor=04192E&color=731FDD)](https://discord.gg/KdQpTzQybu)

Back to [📑 Index](#-index).
# 💾 How to download the files of this repository
Just simply click the green box with the word that says $\color{#00CC00} \mathtt{'Code'}$ and then it will open a small window. On that window, select the option $\color{#FF8800} \mathtt{'Download ZIP'}$. It will download all the files in your PC. When the process is done, go to where the ZIP file was downloaded and extract its content there. After that you are free to use the tool 😉.

# ☑️ How to use quickbms
[![Youtube](https://img.shields.io/badge/RogerRoger%20tutorial%20about%20it-Video%20link-7289DA.svg?logo=Youtube&style=flat-circle&labelColor=FFFFFF&color=C00808&logoColor=FF0000)](https://www.youtube.com/watch?v=_EQ3hPrh0V8)

[![Youtube](https://img.shields.io/badge/linterni's%20tutorial%20to%20start%20modding%20TCS-Video%20link-7289DA.svg?logo=Youtube&style=flat-circle&labelColor=FFFFFF&color=C00808&logoColor=FF0000)](https://www.youtube.com/watch?v=gchonYfKs04)

Back to [📑 Index](#-index).
# ⚠️ Problems reported
<details><summary><h2>1. Why the tool doesn't work after double clicking it?</h2></summary>
In case that happened, then do the following:

1.- In the tab above, go to File -> Open Windows Powershell.

2.- Put the name of the file you wanna open with its extension.

3.- Follow the steps to be able to extract dat files.
</details>
<details><summary><h2>2. Why the tool doesn't extract the files contained inside the DAT files?</h2></summary>
It might be due to these reasons:

1.- The bms script you selected is not the correct one.

2.- The DAT file is not valid (E.g. Transformers The Game for Xbox 360).

3.- The DAT files are corrupted (careful with extracting DAT files from PS3 or Xbox 360 ISOs, check problem nº5).

4.- The DAT file is too big to be processed on the memory (quickbms shows the error memory allocation problem, happens with the DAT files from TCS PS3).
</details>
<details><summary><h3>3. I've opened DAT files with another program and they're no longer DAT.</h3> <h4>What can I do?</h4></summary>
The DAT files have not been altered, just your computer shows them with a different icon. What you need to check to make sure they are still DAT files is the type of file they are. If it says `DAT file` then it's still a DAT file and so it can be extracted easily with quickbms following the correct steps.

If they aren't DAT files anymore, then get the original DAT files and DO NOT try to open them again with a different program.
</details>
<details><summary><h2>4. When I open quickbms, it closes. What I can do?</h2></summary>
Right click on it, run it as administrator and done. This problem has been reported to happen on Windows 11 so by running the tool as administrator solves the problem.
</details>
<details><summary><h2> 5. How can I extract the files inside a console version of the game?</h2></summary>
It depends of which console version of the game we're talking about:

- $\color{#FF8800} \mathtt{\textbf{\large{Android and IOS}}}$: the game files are all contained in the `.obb` file, so extract it using quickbms like it was a DAT file.

- $\color{#FF8800} \mathtt{\textbf{\large{Xbox 360}}}$: sometimes the game comes compressed on an ISO file and we can see it contains 2 folder called `AUDIO_TS` and `VIDEO_TS`. In that case you need a tool that has been built specifically to extract Xbox 360 ISO files like **XBOX 360 ISO Extract**. By opening the tool and selecting the ISO of the game you wanna decompress, it will extract all the content from it and everything will look normal now (there would be the case in which there are no DAT files and everything is extracted, so $\color{#0066FF} \mathtt{\textbf{\large{say thanks to the devs}}}$ :innocent:).

- $\color{#FF8800} \mathtt{\textbf{\large{Wii}}}$: sometimes the game comes compressed on a `.wbfs` file or `.nkit.iso` file. Depending of which of them you have to deal with you will need:
  - **Nkit**: to extract the `.nkit.iso` file or convert it to an iso file you can extract later.
  - **Wbfs to ISO**: to convert the `.wbfs` file to an iso file you can later extract using Nkit.
  SInce here just follow the steps (there would be the case **again** in which there are no DAT files and everything is extracted, so $\color{#0066FF} \mathtt{\textbf{\large{say thanks again to the devs}}}$ :innocent:).

- $\color{#FF8800} \mathtt{\textbf{\large{PS3}}}$: the files are all contained in a `.pkg` file, so using **PSN PKG Decryptor & Extractor** should convert it to iso. From there just extract the files of the iso normally. If there were no DAT files and some weird files ended on 60000 or something like that, **those files are a fragmented DAT file** you will need to join using a hex editor to be able to extract the content inside of it.

- $\color{#FF8800} \mathtt{\textbf{\large{PSP}}}$: Use UMGDen to extract the files. A good example of having issues here with DAT files is **Transformers: The Game** on this console version. **There are no DAT files** and the files contained inside of it contain unknown extensions that make us $\color{#FF0000} \mathtt{\textbf{\large{unavailable to extract them}}}$.
</details>

<details><summary><h2> 6. How can I extract the files on macOS and Linux?</h2></summary>
Fortunately, quickbms can be run on both of them. You can download them here:
   
- $\color{#00FF00} \mathtt{\textbf{\large{Linux}}}$: [Download](https://aluigi.altervista.org/papers/quickbms-src-0.12.0.zip). The game will have the same structure as normal: DAT files you have to extract (remember to use the bms files left on this repository to not have problems extracting).
 
- $\color{#00FF00} \mathtt{\textbf{\large{macOS}}}$: On macOS there is an extra step to take. There is a file inside the folder `Contents` (located in `GameName`/`GameName`.app/) and this file has as extension `.dmg`. This file contains the DAT files of the game so we have to extract it. It can either be extracted using 7zip for macOS or using DMG Extractor. Once it's done, now we can see we have a Data folder with all the DAT files there. To use quickbms on macOS, you can get it from here: [Download](https://github.com/ryopei/quickbms-macos/releases/tag/v0.8.0) (remember to use the bms files left on this repository to not have problems extracting).
</details>

Back to [📑 Index](#-index).
