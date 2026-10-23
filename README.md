# Birthday surprise

This is a small Python-served birthday game with four stages. It uses only the
Python standard library.

## Run locally

On Windows, open a terminal in this folder and run:

```powershell
py app.py
```

Then open <http://127.0.0.1:8000> in a browser. If `py` is unavailable, install
Python 3 and run `python app.py` instead.

The letter stage displays a slideshow of the four bundled photos in `pic/`.
If the page still shows the old photo-upload control, restart the server from
this project folder and hard-refresh the browser (`Ctrl+F5`).

The birthday music attempts to autoplay as a looping YouTube embed from the
start of the game until the candles are blown out. The browser must be online
to load it. Autoplay settings may block playback; use the music button in the
header to show the YouTube player, then press its play control.

After blowing out the candles, the local video at `video/01.mp4` plays. The
letter stage becomes available after the video finishes.
