# Payload-Dumper
Extract only boot.img, vbmeta.img and recovery.img from payload.bin files from Android firmwares like Xiaomi or OnePlus.

This code runs on Python3
If you want any other partition to be extracted, just add the name in line 94



HOW TO RUN?

First clone this repo or download zip and extract,

install dependencies from requirements.txt file using pip

[ pip install -r requirements.txt ]

put the payload.bin file in the same directory as this repo, run the command 

[ python dump.py payload.bin ]

it will extract boot.img, vbmeta.img and recovery.img in "output" folder
