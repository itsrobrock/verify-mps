# Verify MPS is used to verify that you have installed PyTorch correctly on Apple Silicon Macs.
This repository is made to follow along with this guide on (Installing ComfyUI on Mac Silicon)https://theaiflows.com/installing-comfyui-on-mac-silicon/

After cloning this repository, run verify.py in the command prompt using the following:
  python3 verify.py

You should see the following
  tensor([1.], device='mps:0')

If not, you did not install the packages correctly. 
