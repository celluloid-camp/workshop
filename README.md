# workshop

Jupyter examples for media experiments.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Also install [ffmpeg](https://ffmpeg.org/) for merging video/audio streams.

## Notebooks

- [`download_youtube.ipynb`](download_youtube.ipynb) — download a YouTube video with `yt-dlp`

```bash
jupyter notebook download_youtube.ipynb
```

Downloaded files are written to `downloads/`.
