# Scaletor

**Scaletor** is a catalog of all the musical scales. It is equipped with a thermodynamical search engine (TSE). It was created together with the manuscript "[The Ising model and random fields of scales](https://arxiv.org/abs/XYZ)" where you can find all the details of the TSE.

**Scaletor** is written in Processing, an IDE capable of producing stand alone java applications. In this repository we make available the packages with the executable files of **Scaletor** for macOS, windows y linux.


# Download

**Scaletor** requires a large display area (2500 x 1330). We make available executables of **Scaletor** for medium and small displays, choose the version that best fits your case.

**Full size** (2500 x 1330):

A.1 [macOS (Intel 64-bit)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-full-macos-intel.zip).

A.2 [macOS (Apple Silicon)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-full-macos-silicon.zip).

B. [windows (Intel 64-bit)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-full-windows.zip).

C. [linux (Intel-64-bit)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-full-linux.zip).

**Medium size** (1920 x 1080 maximum):

A.1 [macOS-medium (Intel 64-bit)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-medium-macos-intel.zip).

A.2 [macOS-medium (Apple Silicon)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-medium-macos-silicon.zip).

B. [windows-medium (Intel 64-bit)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-medium-windows.zip).

C. [linux-medium (Intel-64-bit)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-medium-linux.zip).

**Small size** (1300 x 750 maximum):

A.1 [macOS-small (Intel 64-bit)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-small-macos-intel.zip).

A.2 [macOS-small (Apple Silicon)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-small-macos-silicon.zip).

B. [windows-small (Intel 64-bit)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-small-windows.zip).

C. [linux-small (Intel-64-bit)](https://github.com/gomiza/scaletor/releases/download/v1.0.0/scaletor-small-linux.zip).

All files in the package are required, including the executable and auxiliary files (three .png images and a text file named .txt, all named as shipped, and there is an additional optional folder with a sample of few symbolic sequences). If necessary, follow [instructions to install standalone Processing applications in your operative system](https://github.com/processing/processing4/wiki/Exporting-Applications#macos).

# Installation

In macOS Intel Core i7 for example, I have to open a terminal and then go to the folder where the **Scaletor**'s files are stored, e.g. by executing a command like

`cd /Users/YourUserName/Applications/scaletor/`

(with your own user name the path that where Scaletor's files have been saved). Then execute

`xattr -d com.apple.quarantine Scaletor.app`

and you should be all set! This process is done only once, henceforth double click on Scaletor to launch (and press the `Esc` key to quit).

# Hot keys

(A) Anchors the base note.

(M) Turns the external magnetic field On and Off.

(R) Changes the rule to play consecutive scales.

(+) Increases the speed at which scales are played.

(-) Decreases the speed at which scales are played.

(H) Changes the speed at which scales are played (min, medium, max).

(F) Freezes the selected scale.

(Del) Deletes the selected scale.

(T) Scrolls the GUI to the corners, in clockwise direction (only for medium and small displays).

# Additional information

For more information visit [**Scaletor**'s official website](https://sites.google.com/im.unam.mx/scaletor).
