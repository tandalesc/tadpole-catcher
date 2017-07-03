# Tadpole Catcher

Forked from bachvudao/tadpole-catcher. Code derived from twneale/tadpoles. Modified to work with Tadpole authentication. Modified to also download report divs as html.

This script will download all images, videos, and reports associated with a Tadpole account.

## Requirements

* `selenium`
* `python 3.3+` (Anaconda3)

## Usage

`python app.py`

On first use, an authentication cookie needs to be generated. Type in your email and password.
The cookie will be saved so subsequent runs will authenticate automatically.

The script will avoid downloading images, videos, and reports that already exist.
