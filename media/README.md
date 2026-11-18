# Media for the home page

| File | What it shows |
| --- | --- |
| `screenshot-1.png` | The main window: three devices in tabs, live charts, log, memory and CPU per process |
| `screenshot-2.png` | The All devices tab |
| `tutorial/<id>.gif` | The "How to use" section and the app's Help > Tutorial, one per topic of `../tutorial.json` |
| `tutorial/big/<id>.gif` | The same at full size, opened by a click |

All of them are made by the app's `tools/tutorial_gifs.py` from the real app with simulated devices
(`tools/device_simulator.py`), so they show no real devices, addresses or passwords. If you replace
them with captures of real devices, blur or crop out IP addresses, user names and passwords first.
Change `MEDIA_REV` in `index.html` after replacing pictures, so browsers load the new ones.
