# Examples

## [Sine Oscillator](https://github.com/everdrone/libsnd/tree/master/examples/sine)

Produces a 440Hz sine wave audio stream through the default system audio channel output.

#### Requirements

* [RtAudio](http://www.music.mcgill.ca/~gary/rtaudio/)

#### Compiling

```bash
g++ sine.cc -o sine.out -lrtaudio -lsnd
```
