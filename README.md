# Pydroid 3 with Termux
## Pydroid 3
Pydroid is a Python IDE for android, it includes `pip` and therefore the possibility to install jupyter-lab. 

* Install "Pydroid 3 - IDE for Python 3" from Google Play in your phone
* Open "Pydroid 3". From the application menu choose "PIP" and on install type `jupyterlab`. See [here](https://stackoverflow.com/a/51581309/2268280) for details. * To check the installation, From the application menu choose "Terminal" and in the terminal prompt type
```bash
/storage/emulated/0 $ jupyter-lab
```
which opens the Jupyter Lab interface in the browser, like in the image below
![img][img/chrome.jpeg]

## Termux
Install "Termux" from Google Play in your phone. Open the application and in terminal prompt type
```bash
termux-setup-storage
```
and in the popup allow Termux to access photos, media, and files on your device.
In particular, the read/write permissions in the `/storage/emulated/0` directory to be shared with Pydroid 3.

Install `git` with
```bash
apt update
apt install git
```

