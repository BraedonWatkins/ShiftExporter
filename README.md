# Unofficial Target Shift Exporter <!-- omit in toc -->

Hey! This is the unofficial Target shift exporter. At the moment it is a bit difficult to work on externally so it's not exactly functional. I've sunk enough time on it but in this iteration I've at least done some housekeeping and updating things.

## Table of Contents <!-- omit in toc -->

- [Setup \& Usage](#setup--usage)
  - [Note: Config File](#note-config-file)
  - [Usage](#usage)
  - [Debugging](#debugging)
- [Contributing](#contributing)

## Setup & Usage

### Note: Config File

[@Chubbygummibear](https://github.com/Chubbygummibear) wrote in the original that all we need to do is change the config file to use our own information but we don't see the variables in `logger.py` so it must have slipped their mind. No shade I promise!

For debugging I just hardcoded lines #69 and #70 because I thought this would be fixed quickly (lol). I intend to fix it but for the moment I want to finish this README therefore the config is **not** updated.

### Usage

Clone the repository and install the requirements to get started! Run the logger with `python logger.py`.

### Debugging

It will stall after line #79. Feel free to up the sleep count and debug in the meantime. Some notes:

- The difference between a manual login and an automated one is some obfuscated variables in the header such as `x-gyjwza5z-a`
  - I had a list of the headers and notes about their differences but I lost the file. RIP.
  - I don't know what these variables refer to or how to format a request using them properly

The stuff after it regards security questions which are deprecated but I have not gotten farther in the file yet.

After it there is logic regarding the google calendar logic.

## Contributing

Feel free to contact me [@braedonwatkins](https://github.com/braedonwatkins) on the matter but of course [@Chubbygummibear](https://github.com/Chubbygummibear) is the original maker of the repo. May reach out if I get anywhere functional with this.

<br><br>

### Good luck and may Bullseye bless you. <!-- omit in toc -->
