---
title: "Resources"
description: ""
---

## FAQ

### I submitted my project before the deadline - why is my grade a 0?

You may have forgotten to click the "Confirm" button after receiving your auto grade. Unfortunately we can't accept this as an excuse as we have no way of determining if you were actually finished ahead of time. Please be careful!

![ATutor confirmation example](./projects/images/atutor_confirm.png)

## Latest Nyquist setup instructions

- Install the Java JDK (if you haven’t already):
  - Download JDK 17 from https://www.oracle.com/java/technologies/downloads/#java17 for your specific operating system and run the installer
  - **Note**: For Macbooks w/ Apple silicon (M1/M2/M3), make sure to select the “ARM64 DMG Installer”
  - **Note**: Make sure you install a recent version of the JDK (>=17). Other common installations of Java (e.g., JRE Version 8) will _not_ run NyquistIDE.
- Install Nyquist
  - Download [latest version of Nyquist](https://sourceforge.net/projects/nyquist/files/nyquist/3.24) and run installer
    - **Note**: For newer Macs w/ Apple Silicon (M1/M2/M3), download `nyquist-install-arm-324.dmg`. For Macs w/ Intel chips, download `nyquist-install-intel-324.dmg`
  - macOS installation
    - Open `nyquist-install-{arm,intel}-324.dmg`
    - Open Finder
    - Press Cmd+Shift+H to navigate to your home directory, drag the “nyquist” folder into it
    - Click on “Applications” on the left side and drag “NyquistIDE” into it
    - Ctrl+Click on NyquistIDE in your Applications and press “Open”
  - Windows installation
    - Double click on `setupnyqiderun324.exe`
    - Click “Run Anyway”
    - Additional troubleshooting information can be found here: https://www.cs.cmu.edu/~rbd/doc/nyquist/index.html

### (Optional) Command Line Nyquist setup instructions

- We strongly recommend students use NyquistIDE for all Nyquist programming this semester.
  However, should you prefer your own IDE, we also provide instructions below on how to interact with the Nyquist interpreter
  through the command line. Proceed with caution - instructors / TAs may be unable to help you with any issues you encounter
  outside of NyquistIDE.
  - Instructions are only provided here for Mac, but Linux usage should be similar
- First, confirm the Nyquist executable exists at the following path:
  - `/Applications/NyquistIDE.app/Contents/Java/ny`
  - It's recommended to add an alias to your `zshrc` (or `bashrc`, if using Bash) to this executable, as below:
    - `alias nyquist=/Applications/NyquistIDE.app/Contents/Java/ny`
- Next, locate your `nyquist` folder from installation, likely at `/Users/[your username]/nyquist`, and confirm
  that it contains a `lib` and `runtime` folder; Add the following to your `zshrc`:
  - `export XLISPPATH=/Users/[your username]/nyquist/runtime:/Users/[your username]/nyquist/lib`
  - Make sure to update the above paths to match your own installation.
  - Now you should be able to able utilize the `nyquist` REPL from anywhere on your system, such as within a VSCode terminal!
- We provide extremely limited support for this option, but here are some tips you may want to keep in mind:
  - `nyquist` opens in Lisp mode; to change to SAL mode, enter the command `(sal)` followed by the return key.
    - This should change your prompt from `>` to `SAL>`
  - To exit `nyquist`, send `exit` while in SAL, followed by `(exit)` when back in Lisp.
  - Audio files produced by `play` are saved at the printed path, usually in your `/tmp` directory.
  - Sound plots, produced by `plot` or `s-plot` are saved as `.dat` files which can be visualized using a third-party tool like `gnuplot` (or even `matplotlib` in `Python` if you desire).
  - To load/run a file, simply call `load "my_file.sal"` while in the SAL prompting mode.
  - You may also wish to install the VSCode syntax highlighting extension called `Nyquist`, available in the Extensions Marketplace.
- Additional documentation is available [here](https://www.cs.cmu.edu/~rbd/doc/nyquist/), under "Command Line"

## Other resources

- [Nyquist user manual](https://www.cs.cmu.edu/~rbd/doc/nyquist/index.html)
- [Audacity user manual](https://manual.audacityteam.org/)
- [ICM Playlist (by Jesse Stiles)](https://open.spotify.com/playlist/3VzPJ5idcjoZghHjuQAZUT?si=IrCH_oZfQqOqoe-RcwN94w&nd=1)
- [Max demos (from Jesse Stiles)](https://drive.google.com/drive/folders/1wC5iP-rP6jvPopqGFO_vD7q6m7Aquwxr)
- Other optional textbooks and resources:
  - [_Algorithmic Composition_](https://press.umich.edu/Books/A/Algorithmic-Composition2) by Mary Simoni and Roger B. Dannenberg. [Link to electronic version in CMU library](https://cmu.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma991019513995704436&context=L&vid=01CMU_INST:01CMU&lang=en&search_scope=MyInst_and_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,algorithmic%20composition).
  - [_The Computer Music Tutorial_](https://www.amazon.com/Computer-Music-Tutorial-second-dp-0262044919/dp/0262044919/ref=dp_ob_title_bk) by Curtis Roads. [Link to electronic version in CMU library](https://cmu.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma991019486715904436&context=L&vid=01CMU_INST:01CMU&lang=en&search_scope=MyInst_and_CI&adaptor=Local%20Search%20Engine&isFrbr=true&tab=Everything&query=any,contains,computer%20music%20tutorial&sortby=date_d&facet=frbrgroupid,include,9019777044576965786&mode=Basic&offset=0). Broader in scope than this course.
- [International computer music association](http://www.computermusic.org/)
