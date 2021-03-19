# Quest-FFmpeg
arm64-v8a libraries for Quest

Command to run:
```
      docker run --rm -v {Path-to-your-copy-of-this-repo}:/mnt/ffmpeg-android-maker -e FAM_ARGS="-abis=arm64 -android=24 -x264 -binutils=llvm" ffmpegarm64:latest
```
