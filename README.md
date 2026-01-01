# musika

*Minimal command-line music player written in Python.*

`pip install musika`

<br>

[![Button Hover](https://img.shields.io/badge/Github-c9510c?style=for-the-badge)](https://github.com/Julynx/musika)
[![Button Hover](https://img.shields.io/badge/PyPi-006dad?style=for-the-badge)](https://pypi.org/project/musika)

<br>

<br>
<p align="center">
  <img width="640" src="https://i.imgur.com/lXdISlv.png">
</p>
<br>

## Usage

```bash
Usage:
    musika [OPTIONS]          Play a random song from '~/Music'.
    musika [FILE] [OPTIONS]   Play a specific song.
    musika [DIR.] [OPTIONS]   Play a random song from a directory.

OPTION:
    --update-interval=<X>   Redraw the UI every X seconds.
    --no-infinite-queue     Stop playback when the song ends.
    --no-clear              Don't clear the screen between UI updates.
                              This may help prevent flickering on
                              some terminals.
    -h, --help              Print this message and exit.
    -v, --version           Print version information and exit.
```
