# SoccerSynth-Detection: A Synthetic Dataset for Soccer Player Detection
[![arXiv](https://img.shields.io/badge/arXiv-xxxx.xxxxx-b31b1b.svg)](https://arxiv.org/abs/xxxx.xxxxx)

<div style="display:flex;">
  <img src="https://github.com/open-starlab/SoccerSynth-Detection/blob/main/img/4.png" alt="Image 1" style="width:40%;">
  <img src="https://github.com/open-starlab/SoccerSynth-Detection/blob/main/img/3.png" alt="Image 2" style="width:40%;">
</div>

**Abstract**

In soccer video analysis, player detection is essential for identifying key events and reconstructing tactical positions. The presence of numerous players and frequent occlusions, combined with copyright restrictions, severely restricts the availability of datasets, leaving limited options such as SoccerNet-Tracking and SportsMOT. These datasets suffer from a lack of diversity, which hinders algorithms from adapting effectively to varied soccer video contexts. To address these challenges, we developed SoccerSynth-Detection, the first synthetic dataset designed for the detection of synthetic soccer players. It includes a broad range of random lighting and textures, as well as simulated camera motion blur. We validated its efficacy using the object detection model (Yolov8n) against real-world datasets (SoccerNet-Tracking and SportsMoT). In transfer tests, it matched the performance of real datasets and significantly outperformed them in images with motion blur; in pre-training tests, it demonstrated its efficacy as a pre-training dataset, significantly enhancing the algorithm's overall performance. Our work demonstrates the potential of synthetic datasets to replace real datasets for algorithm training in the field of soccer video analysis.

link to the dataset:

https://drive.google.com/file/d/1UJd9ayx5_cXW28NEE8jlLO9oThleZ-y7/view?usp=drive_link

link to the generator(Win64):

https://drive.google.com/drive/folders/1sBwTbRcQ2eWgHByByxsp_JuPaMtd8_ME?usp=drive_link

link to the result of pre-train experiment:

https://drive.google.com/drive/folders/1IfZAtWpjXK4JtugInxTmCCtCnIFmRxk1?usp=drive_link

link to the result of transfer experiment:

https://drive.google.com/drive/folders/1JyCxlO7V9_3ywH-IN1TNLxxwhaEfdkBl?usp=drive_link

link to yolo
https://github.com/autogyro/yolo-V8

Method to convert into yolo format
1. clone the repo
```
git clone
```
2. cd to the repo
```
cd ./SoccerSynth-Detection
```
3. run the script
```
python xx.py
```

## Developer
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<!-- [![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-) -->
<!-- ALL-CONTRIBUTORS-BADGE:END -->

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
<td align="center" valign="top" width="14.28%" style="min-height:150px;">
    <a href="https://github.com/qinhaobin1997">
        <img src="https://github.com/qinhaobin1997.png" style="height:100px; width:100px;" alt="Haobin Qin"/><br />
        <sub><b>Haobin Qin</b></sub>
    </a>
    <br /><a href="#Developer-HaobinQin" title="Lead Developer">💻</a>
</td>
<td align="center" valign="top" width="14.28%" style="min-height:150px;">
    <a href="https://github.com/calvinyeungck">
        <img src="https://github.com/calvinyeungck.png" style="height:100px; width:100px;" alt="Calvin Yeung"/><br />
        <sub><b>Calvin Yeung</b></sub>
    </a>
    <br /><a href="#Coordinator-CalvinYeung" title="Developer">💻</a>
</td>
<td align="center" valign="top" width="14.28%" style="min-height:150px;">
    <a href="https://github.com/Rikuhei-ynwa">
        <img src="https://github.com/Rikuhei-ynwa.png" style="height:100px; width:100px;" alt="Rikuhei Umemoto"/><br />
        <sub><b>Rikuhei Umemoto</b></sub>
    </a>
    <br /><a href="#Coordinator-RikuheiUmemoto" title="Developer">💻</a>
</td>
<td align="center" valign="top" width="14.28%" style="min-height:150px;">
    <a href="https://github.com/keisuke198619">
        <img src="https://github.com/keisuke198619.png" style="height:100px; width:100px;" alt="Keisuke Fujii"/><br />
        <sub><b>Keisuke Fujii</b></sub>
    </a>
    <br /><a href="#lead-KeisukeFujii" title="Team Leader">🧑‍💻</a>
</td>


  </tbody>
</table>
