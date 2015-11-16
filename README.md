# ffmpeg-lame-opus
ffmpeg build with lame and opus for Heroku buildpacks

Used by [this buildpack](https://github.com/Olegas/heroku-buildpack-ffmpeg)

Compiled with [oficial guide](https://trac.ffmpeg.org/wiki/CompilationGuide/Ubuntu) on Heroku one-off dyno using `heroku run bash --app ...`
using `--enable-opus` and `--enable-lame`
