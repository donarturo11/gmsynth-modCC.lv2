gmsynth-modCC.lv2 - General MIDI Synth
================================

gmsynth-modCC.lv2 is a General MIDI Sample Player Plugin. This is based on original soundfont but modified to controlling modulators with Control Change with GS compatibility.

Install
-------

Compiling gmsynth requires the LV2 SDK, gnu-make, a c++-compiler.

```bash
  git clone https://github.com/donarturo11/gmsynth-modCC.lv2.git
  cd gmsynth-modCC.lv2
  make
  sudo make install PREFIX=/usr
```

Note to packagers: the Makefile honors `PREFIX` and `DESTDIR` variables as well
as `CXXLAGS`, `LDFLAGS` and `OPTIMIZATIONS` (additions to `CXXFLAGS`), also
see the first 10 lines of the Makefile.
