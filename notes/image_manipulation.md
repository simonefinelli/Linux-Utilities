# Image Manipulation

## Create a GIF starting from a video
```Bash
ffmpeg -i video.mp4 -vf "fps=30,scale=720:-1:flags=lanczos" -c:v gif -b:v 2M -q:v 10 output.gif
```