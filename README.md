A static build of ffmpeg (built with [https://github.com/stvs/ffmpeg-static](https://github.com/stvs/ffmpeg-static))

FFmpeg output:

ffmpeg version 2.1-static Copyright (c) 2000-2013 the FFmpeg developers
  built on Nov 18 2013 09:38:34 with gcc 4.6 (Ubuntu/Linaro 4.6.3-1ubuntu5)
  configuration: --prefix=****/ffmpeg-static/target --extra-cflags='-I****/ffmpeg-static/target/include -static' --extra-ldflags='-L****/ffmpeg-static/target/lib -lm -static' --extra-version=static --disable-debug --disable-shared --enable-static --extra-cflags=--static --disable-ffplay --disable-ffserver --disable-doc --enable-gpl --enable-pthreads --enable-postproc --enable-gray --enable-runtime-cpudetect --enable-libfaac --enable-libmp3lame --enable-libtheora --enable-libvorbis --enable-libx264 --enable-libxvid --enable-bzlib --enable-zlib --enable-nonfree --enable-version3 --enable-libvpx --disable-devices
  libavutil      52. 48.100 / 52. 48.100
  libavcodec     55. 39.100 / 55. 39.100
  libavformat    55. 19.104 / 55. 19.104
  libavdevice    55.  5.100 / 55.  5.100
  libavfilter     3. 90.100 /  3. 90.100
  libswscale      2.  5.101 /  2.  5.101
  libswresample   0. 17.104 /  0. 17.104
  libpostproc    52.  3.100 / 52.  3.100
Hyper fast Audio and Video encoder


Built for internal use by this custom [buildpack](https://github.com/integricho/heroku-buildpack-python-ffmpeg2.1-all-codecs).
