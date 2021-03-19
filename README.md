# Quest-FFmpeg
arm64-v8a libraries for Quest

CD into {Path-to-your-copy-of-this-repo}/tools/docker/
and run the following commands
Commands to run (requires docker):
```
$ docker build -t ffmpegarm64 .
$ docker run --rm -v {Path-to-your-copy-of-this-repo}:/mnt/ffmpeg-android-maker -e FAM_ARGS="-abis=arm64 -android=24 -x264 -binutils=llvm" ffmpegarm64:latest
```
