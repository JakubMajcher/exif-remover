# exif-remover

Exif (Exchangeable Image File Format) is a metadata of photo. There may be information about the date the photo was taken, where it was taken, or with what device.

Script removes all of this exif data. Only orientation of picture is saved. Apart from that name of photo is changing and script is adding datatime on prefix as "[YYYY-MM-dd HH-mm-ss] - ".

## Usage

Copy-paste all photos to process to dictonary "to_process" and run ```./remover to_process```. All processed photos will show up in "Converted" dictonary and originals in "Original".

## License

[MIT](https://choosealicense.com/licenses/mit/)