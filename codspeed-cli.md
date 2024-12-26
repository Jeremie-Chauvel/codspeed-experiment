# codspeed CLI

## learnings

- needs to run as sudo (for setarch), run `sudo -v` before
- fork for pop os archi, easy to install once built from source (no docs though)
- assume using system python, you need to copy a shared lib in your virtual env:
  - for my python version using uv : `ln -srf ~/.local/share/uv/python/cpython-3.12.6-linux-x86_64-gnu/lib/libpython3.12.so.1.0 ./.venv/lib/`
