# Nimsoloud

A static wrapper of my fork of [Soloud](https://github.com/Anuken/soloud).

**This is not a binding to the main Soloud library** - it uses my stripped-down fork.

Notable differences:

- Only ogg decoding is supported, to reduce binary size and improve compilation speeds
- All audio sources except Wav and WavStream have been removed