youtube-downloader
==================
An ugly but working solution for downloading youtube videos.

This was one of my first bash scripts, so do not expect so much.

This script prints each download url for all formats of a youtube video.

## Usage

Youtube's video id is needed, so if you don't know what it is, or how to get a youtube's video id, [watch this](https://www.youtube.com/watch?v=EKyirtVHsK0)

After getting the youtube's video id, we proceed to get the urls for download.

```sh
./youtube.sh video_id


## FORMAT 1
URL1
---------------
## FORMAT 2
URL2
---------------
...

```

Now just choose the format, copy the url and open it in the browser, or since we are in the console, use the `open` command.

`open YOUTUBEVIDEOURL`

## TODOS
- Select the wanted format from the terminal (something like yeoman's generators).
- Copy link to clipboard or download the video with `wget` (a youtube's session cookie is needed).







