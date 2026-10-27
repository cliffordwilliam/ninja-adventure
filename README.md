# Ninja Adventure

This is a top-down, turn-based video game that uses assets from [Ninja Adventure asset pack](https://pixel-boy.itch.io/ninja-adventure-asset-pack). I created this repository because I liked the look of the assets and wanted to make a game with them for fun. The assets are released under the Creative Commons Zero (CC0) license, made by [Pixel-Boy](https://twitter.com/2Pblog1) and [AAA](https://www.instagram.com/challenger.aaa/?hl=fr).

## Project details

When I started this project, the latest version of Python was 3.15, so the project requires Python 3.15 or later.

This project also uses `uv` version 0.13.5 to manage Python versions and dependencies.

## Getting started

I've included the lock file in the repository, so please use `uv` to install the exact dependency versions specified in the lock file. Run the following command to install the dependencies into the `.venv` directory:

```bash
uv sync
```

This ensures that you use the same dependency versions as I do.

To run the project, use the following command:

```bash
uv run ninja-adventure
```

This command runs the `main()` function in the `main.py` module in the `src/ninja_adventure` package.

