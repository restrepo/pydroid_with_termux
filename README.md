# Pydroid 3 with Termux
## Pydroid 3
Pydroid is a Python IDE for android, it includes `pip` and therefore the possibility to install jupyter-lab. 

* Install "Pydroid 3 - IDE for Python 3" from Google Play in your phone
* Open "Pydroid 3". From the application menu choose "PIP" and on install type `jupyterlab`. See [here](https://stackoverflow.com/a/51581309/2268280) for details. * * To check the installation, From the application menu choose "Terminal" and in the terminal prompt type
```bash
jupyter-lab
```
which opens the Jupyter Lab interface in the browser, like in the image in [section below](https://github.com/restrepo/pydroid_with_termux/blob/main/README.md#termux)

## Termux
* Install "Termux" from Google Play in your phone. Open the application and in terminal prompt type
```bash
termux-setup-storage
```
and in the popup allow Termux to access photos, media, and files on your device.
In particular, the read/write permissions in the `/storage/emulated/0` directory to be shared with Pydroid 3.

* Install `git` with
```bash
apt update
apt install git
```
* Go to "Pydroid 3" directory and creates a working directory, e.g, `prog`
```bash
cd /storage/emulated/0
mkdir prog
cd prog
```

* Download some GitHub repository with Jupyter notebooks in the working directory
```bash
git clone https://github.com/restrepo/ComputationalMethods.git
```
* Open some notebook...
![img](https://github.com/restrepo/pydroid_with_termux/raw/main/img/jupyter.jpeg)

## Hacker's Keyboard
It is recommended to have a better keyboard for programming editing
* Install "Hacker's Keyboard" from Google Play in your phone
* Got to the "Manage keyboards" settings and activate "Hacker's Keyboard"
* From the Gboard keep the space bar pressed until the dialog to switch keybards appears and change to "Hacker's Keyboard" 
* Hit the configuration key between to the right to microphone one. 
* Go to the Keyboard mode, portrait and switch to the 5-row compact layout

