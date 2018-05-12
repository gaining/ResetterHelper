# Resetter Helper v1.0
- Resetter only needs two files to be compatible with a distro, the first is a stock manifest file, the second is the stock userlist. ResetterHelper doesn't need to be installed and can be run on a new system to generate those files.
- With the help of volunteers running this program on a stock debian based system and submitting their generated files, Resetter will be compatible with virtually any debian based os whether x86, amd64 or arm.
- This is the program that will help reseter spread to other debian based distros.
- Written in python 3.5 and PyQt5

# How to use
(Using GUI)

- Download the program found [here](https://github.com/gaining/ResetterHelper/releases/latest) then on the terminal, run the following commands:
- Extract the tar.gz file, by right clicking, then select "*extract files*"
- Double click on *ResetterHelper* Binary to run it
- Press generate
- send me the generated files by email or create a pull request which adds these files to the data folder which contains the manifest (I'll write a separate instruction for this)
- Make sure to only run this program on a **stock distro with no added packages other than the preinstalled ones**

(Using CLI)

- If you decide to use the CLI way, I'll assume your know your way around the terminal. Run the following commands:
- 1. `tar xvzf ResetterHelper.tar.gz`
- 2. `cd ResetterHelper`
- 3. `chmod +x ResetterHelper`
- 4. `./ResetterHelper`


# Notes
- A complete cli version of this small program will be released once I find enough time to make it.
- The goal of this program is to help make *Resetter* self sustainable for a bit without me having to updated it all the time.



# Bug reports

- If you find a bug or problem please create an issue on github.
- If you do not have a github account do not hesitate to contact me and send your bug report to gaining7@outlook.com.

# Options

- Generate the manifest of a distro
- Generate the entire userlist of a distro
- Compare previous files together

# Officially supported distro architectures [32-bit, 64-bit, arm]

This program should run on any Linux distros as far as I know, however, it will tell you whether your distro can be supported or not.

# Donate
Please show your support by donating.
[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=8FET8RGU2ZKQ8)

