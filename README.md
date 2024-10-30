# smallertif
Create smaller TIF file with downsampling and JPEG compression

## Command Line Parameters
-f / --file: file data source
-t / --type: target compression (TIFF/JPEG, default: TIFF)
-ov / --overviews: create overview levels (default: "2 4 8 16 32")

## Usage Example
smallertif -f largefile.tif -t JPEG -ov "2 4 8 16" -o small.tif
