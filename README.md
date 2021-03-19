# JupyterLab in Pydroid 3 with Termux (and Hacker's Keyboard)
## Pydroid 3
"Pydroid 3" is a Python IDE for android, it includes `pip` and therefore the possibility to install Jupyter or JupyterLab. 

* Install "Pydroid 3 - IDE for Python 3" from Google Play in your phone
* Open "Pydroid 3". From the application menu choose "PIP". 
* Choose "QUICK INSTALL" and search and install `jupyter` (the old notebook interface), and maybe `matplotlib`, `numpy`, `pandas` and `scipy`, etc.
* To check the installation, from the application menu choose "Terminal" and in the terminal prompt, type
```bash
jupyter-notebook
``` 
> which would open the JupyterLab interface in the browser. It opens a light interface more well suited for cellphone screens (Each cell includes an execution button)
* Optionaly you could install instead the `jupyterlab`: Choose PIP → INSTALL and type `jupyterlab`. See [here](https://stackoverflow.com/a/51581309/2268280) for details. In the terminal prompt, type: `jupyter-lab`, which would open the JupyterLab interface in the browser as shown in the image before the [last section](https://github.com/restrepo/pydroid_with_termux/blob/main/README.md#hackers-keyboard).
* In both cases you can close the aplication from the "Terminal" by using the `<CTRL>+c` key shortcut (see [last section](https://github.com/restrepo/pydroid_with_termux/blob/main/README.md#hackers-keyboard) to install a shortcuts-enabled keyboard )

## Termux
* Install Termux from Google Play in your phone. Open the application, then in the terminal prompt, type
```bash
termux-setup-storage
```
and in the emergent popup allows "Termux to access photos, media, and files on your device".
In particular, this would allow for read/write permissions in the `/storage/emulated/0` directory to be shared with "Pydroid 3".

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

* In this working directory, download some GitHub repository which includes some Jupyter notebooks 
```bash
git clone https://github.com/restrepo/ComputationalMethods.git
```
* From the Jupyter or JupyterLab interface in the browser, open some notebook...
![img](https://github.com/restrepo/pydroid_with_termux/raw/main/img/jupyter.jpeg)

## Hacker's Keyboard
It is recommended to have a better keyboard for easier programming editing:
* Install "Hacker's Keyboard" from Google Play in your phone
* Go to the "Manage keyboards" settings and activate "Hacker's Keyboard": Settings → System → "Languages & Input" → "Virtual keyboard" → "Manage keyboards".
* From the Gboard keep the space bar pressed until the dialog to switch keyboards appears, and then change to "Hacker's Keyboard". Hit the configuration key situed on the right of microphone key (Or choose the "Hacker's Keyboard" icon a choose SETTINGS)
* Select "Keyboard mode, portrait" and switch to the 5-row compact layout

