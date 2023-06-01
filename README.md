# runpod-sd-webui-cnet
Init notebook for installing ControlNet (and other models/extensions) to the RunPod StableDiffusion image

How to use:
1. Create an instance on runpod.io (or another similar website like vast.ai, tensordock.com etc) with runpod/stable-diffusion image (tested with runpod/stable-diffusion:web-automatic-6.0.1).
2. Login with Jupyter or SSH and run `git clone git@github.com:brannt/runpod-sd-webui-cnet.git`.
3. Open `init.ipynb`, execute first cell, then select the models, inversions, extensions etc that you want to install and click Run Interact.
4. In the SD WebUI, click Reload UI so that the new extensions are loaded.
