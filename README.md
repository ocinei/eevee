# eevee
Eevee is trying to implement a suncas tracker. 

- [How To Install DeepLabCut — DeepLabCut](https://deeplabcut.github.io/DeepLabCut/docs/installation.html)
- Core functions of deeplabcut are listed in [Using DeepLabCut for 3D markerless pose estimation across species and behaviors | Nature Protocols](https://www.nature.com/articles/s41596-019-0176-0)
- Video for analysis: [Vole, Mouse & Shrew Encounter - YouTube](https://www.youtube.com/watch?v=9yNMmHjczsU)

Please follow the procedures below to use deeplabcut:

For AppleM1/M2 chips:
```
conda create -n DLC python=3.9
conda activate DLC
pip install "notebook<7.0.0" "tensorflow-macos<2.13.0" "tensorflow-metal" 
pip install "deeplabcut[gui]"
```

and install all the dependencies in the requirements.txt file and the yaml file.
Note that `conda install pytables` may need to be runned if some errors persist during the installation of pytables via pip. 

Also run `pip install 'deeplabcut[gui]'` to enable the GUI.
