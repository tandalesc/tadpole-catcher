# Tadpole Catcher

Forked from bachvudao/tadpole-catcher. code derived from twneale/tadpoles. Modified to work with Tadpole authentication.

This script will download all images and videos associated with a Tadpole account.

## Requirements

* `selenium`
* `python 3.6` (Anaconda3)

## Usage

`python app.py`

On first use, an authentication needs to be generated. Type in your email and password. The cookie will be saved so subsequent runs will authenticate automatically.

The script will avoid downloading already existing images and videos and will download every image/video it can find.
