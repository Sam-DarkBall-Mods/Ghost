# Ghost

[![CI](https://github.com/Sam-DarkBall-Mods/Ghost/actions/workflows/ci.yml/badge.svg)](https://github.com/Sam-DarkBall-Mods/Ghost/actions/workflows/ci.yml)

Ghost adds a small fixed wing UAV for BLUFOR, OPFOR and Independent. The three
variants share the same aircraft and differ by side. There is also a small
sound script that occasionally plays crew audio while the UAV engine is
running.

## Requirements

- Arma 3 2.22 or newer

## Building

```bash
python3 -B -m unittest discover -s tests -p "test_*.py" -v
hemtt check
hemtt build --no-bin
```

The `ghost` PBO prefix and existing vehicle class names are part of the mod's
public interface and are not renamed in patch releases.

## License

Code and configs use GPL-2.0-or-later. The aircraft assets and audio use APL-SA.
See [LICENSES.md](LICENSES.md).
