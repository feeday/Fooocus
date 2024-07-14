### Colab

(Last tested - 2024 Mar 18 by [mashb1t](https://github.com/mashb1t))

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lllyasviel/Fooocus/blob/main/fooocus_colab.ipynb) | Fooocus Official

```
!pip install pygit2==1.12.2
%cd /content
!git clone https://github.com/lllyasviel/Fooocus.git
%cd /content/Fooocus
!python entry_with_update.py --share --always-high-vram
```

```
python3 -m venv myenv
source myenv/bin/activate
pip install pygit2==1.12.2pip install transformers torch
pip install gradio
pip install --upgrade pip
pip install --upgrade torch
pip install --upgrade torchsde
git clone https://github.com/lllyasviel/Fooocus.git
cd Fooocus/
python entry_with_update.py --share --always-high-vram
```

```
prompt
man

negative_prompt
unrealistic, saturated, high contrast, big nose, painting, drawing, sketch, cartoon, anime, manga, render, CG, 3d, watermark, signature, label

style_selections
Fooocus V2,Fooocus Photograph,Fooocus Negative

performance_selection
Speed

sharpness
2

guidance_scale
3

refiner_switch
0.5
```
