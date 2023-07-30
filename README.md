# eevee
Eevee is trying to implement a suncas tracker. 

- [How To Install DeepLabCut — DeepLabCut](https://deeplabcut.github.io/DeepLabCut/docs/installation.html)
- Core functions of deeplabcut are listed in [Using DeepLabCut for 3D markerless pose estimation across species and behaviors | Nature Protocols](https://www.nature.com/articles/s41596-019-0176-0)

Please follow the procedures below to use deeplabcut:

For AppleM1/M2 chips:
`conda create -n deeplabcut_apple_mchip python=3.9
conda activate deeplabcut_apple_mchip
pip install "notebook<7.0.0" "tensorflow-macos<2.13.0" "tensorflow-metal" 
pip install "deeplabcut[gui]"`

