# videoFromPhoto 

A bash script.
Creates a video suitable for Instagram from static picture and audio.

Usage:

```
videoFromPhoto -a <audio file> -p <photo file> <output file>
```

To run the script, you need ffmpeg installed on your computer.

If a `$INSTAGRAM` is set, the output file will be written to `$INSTAGRAM/<output file>`
