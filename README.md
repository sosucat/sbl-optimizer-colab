<p align="left">
<a href="#-english">🔤 English</a> | <a href="#-日本語">🇯🇵 日本語</a>
</p>

---

## English

# 🐐 Advanced Colab Notebook for sbl-optimizer: Print Pattern Optimizer for [Swell by Light](https://sites.gatech.edu/futurefeelings/2025/03/07/swell-by-light-tei-25/)
[![Advanced Colab](https://img.shields.io/badge/Try_This_Notebook-black?logo=googlecolab)](https://colab.research.google.com/drive/1Df32_XEfXZwHhXW8_8GQt3X7Hf300CxG?usp=sharing)

[![PyPI version](https://badge.fury.io/py/sbl-optimizer.svg)](https://badge.fury.io/py/sbl-optimizer)
[![GitHub](https://img.shields.io/badge/GitHub_repo-black?logo=github)](https://github.com/sosucat/sbl-optimizer)

[![Homepage](https://img.shields.io/badge/🔗_Homepage-black)](https://sites.gatech.edu/futurefeelings/2025/03/07/swell-by-light-tei-25/)
[![Author](https://img.shields.io/badge/Author-black?logo=googlescholar&logoColor=white)](https://sosuke-ichihashi.com/)
[![Research paper](https://img.shields.io/badge/Research_Paper-black?logo=acm)](https://doi.org/10.1145/3689050.3704420)
[![Fabrication](https://img.shields.io/badge/🔗_Fabrication-black)](https://sites.gatech.edu/futurefeelings/2025/07/23/make-puffy-patterns-with-light/)
[![Watch fabrication demo on YouTube](https://img.shields.io/badge/Fabrication-750014?logo=youtube)](https://youtu.be/LomVS_jHxl0?feature=shared)

Welcome to **sbl-optimizer**, a friendly tool that turns your images into printable patterns for 2.5D raised textures!  
**This notebook is an advanced version** walking through all the codes. You can upload a picture, run cells, and get an optimized pattern you can print, shine light, and watch pop up like magic.
If you just want to use sbl-optimizer without minding the coding, check out the simplified Colab notebook:

[![Simpler Colab](https://img.shields.io/badge/Simpler_Colab_Notebook-black?logo=googlecolab)](https://colab.research.google.com/drive/1Kpvq15wZrzsnQI28_JfkDSqCwT1ouyxj?usp=sharing)

---


![A printed pattern's shades change as the optimization progresses, and the resulting temperature distribution gets closer to the intended pattern.](https://sites.gatech.edu/futurefeelings/files/2025/03/opt_step.gif)

Optimization of the printed pattern results in a uniform temperature pattern (right) closely matching the original pattern (left). In this example, the leaves are over-heated while the stems are under-heated before the optimization.
As the iteration number goes up, the leaves' temperature goes down while the stems' goes up, resulting in a more uniform temperature distribution.

---


# Credits & License
## License
>This project is licensed under the [MIT License](https://github.com/sosucat/sbl-optimizer-colab/blob/main/LICENSE).


## Developer
>Sosuke Ichihashi

> [![Sosuke Ichihashi](https://img.shields.io/badge/Sosuke_Ichihashi-black?logo=googlescholar&logoColor=white)](https://sosuke-ichihashi.com/)
[![@sosucat](https://img.shields.io/badge/@sosucat-black?logo=github&logoColor=white)](https://github.com/sosucat)
[![@RefreshSource](https://img.shields.io/badge/@RefreshSource-black?logo=x&logoColor=white)](https://x.com/refreshsource)


## Cite this work
> If you use **sbl-optimizer** in your research or projects, please cite:
* Sosuke Ichihashi, Noura Howell, and HyunJoo Oh. 2025.\
Swell by Light: An Approachable Technique for Freeform Raised Textures. \
In Proceedings of the Nineteenth International Conference on Tangible, Embedded, and Embodied Interaction (TEI '25). Association for Computing Machinery, New York, NY, USA, Article 45, 1–16. https://doi.org/10.1145/3689050.3704420
```bibtex
@inproceedings{10.1145/3689050.3704420,
author = {Ichihashi, Sosuke and Howell, Noura and Oh, HyunJoo},
title = {Swell by Light: An Approachable Technique for Freeform Raised Textures},
year = {2025},
isbn = {9798400711978},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3689050.3704420},
doi = {10.1145/3689050.3704420},
booktitle = {Proceedings of the Nineteenth International Conference on Tangible, Embedded, and Embodied Interaction},
articleno = {45},
numpages = {16},
keywords = {2.5D fabrication, Personal fabrication, tactile rendering},
location = {Bordeaux / Talence, France},
series = {TEI '25}
}
```


---

## 日本語

# 🐐 sbl-optimizer 上級者向け Colab ノートブック：[Swell by Light](https://sites.gatech.edu/futurefeelings/2025/03/07/swell-by-light-tei-25/) の印刷パターン最適化ツール
[![Advanced Colab](https://img.shields.io/badge/Try_This_Notebook-black?logo=googlecolab)](https://colab.research.google.com/drive/1Df32_XEfXZwHhXW8_8GQt3X7Hf300CxG?usp=sharing)

[![PyPI version](https://badge.fury.io/py/sbl-optimizer.svg)](https://badge.fury.io/py/sbl-optimizer)
[![GitHub](https://img.shields.io/badge/GitHub_repo-black?logo=github)](https://github.com/sosucat/sbl-optimizer)

[![Homepage](https://img.shields.io/badge/🔗_Homepage-black)](https://sites.gatech.edu/futurefeelings/2025/03/07/swell-by-light-tei-25/)
[![Author](https://img.shields.io/badge/Author-black?logo=googlescholar&logoColor=white)](https://sosuke-ichihashi.com/)
[![Research paper](https://img.shields.io/badge/Research_Paper-black?logo=acm)](https://doi.org/10.1145/3689050.3704420)
[![Fabrication](https://img.shields.io/badge/🔗_Fabrication-black)](https://sites.gatech.edu/futurefeelings/2025/07/23/make-puffy-patterns-with-light/)
[![Watch fabrication demo on YouTube](https://img.shields.io/badge/Fabrication-750014?logo=youtube)](https://youtu.be/LomVS_jHxl0?feature=shared)

**sbl-optimizer** は、画像を印刷可能な 2.5D テクスチャパターンへと変換するためのフレンドリーなツールです。  
**このノートブックは上級者向けバージョン**で、全てのコードのステップを丁寧に解説しています。画像をアップロードしてセルを実行することで、最適化されたパターンを生成し、印刷し、光を当ててデザインが立体的に浮き上がる様子を観察できます。

コードの詳細を気にせずすぐに試したい場合は、以下の簡易版ノートブックをご利用ください：

[![Simpler Colab](https://img.shields.io/badge/Simpler_Colab_Notebook-black?logo=googlecolab)](https://colab.research.google.com/drive/1Kpvq15wZrzsnQI28_JfkDSqCwT1ouyxj?usp=sharing)

---

![最適化によって印刷パターンの濃淡が変化し、温度分布が意図したデザインに近づいていく様子](https://sites.gatech.edu/futurefeelings/files/2025/03/opt_step.gif)

印刷されたパターンを最適化することで、最終的な温度分布（右）が元のデザイン（左）により近づきます。  
この例では、最適化前に葉の部分は加熱しすぎ、茎の部分は加熱不足でした。最適化を繰り返すことで、温度分布が均一になっていきます。

---

# クレジットとライセンス

## ライセンス
>このプロジェクトは [MIT ライセンス](https://github.com/sosucat/sbl-optimizer-colab/blob/main/LICENSE) のもとで公開されています。

## 開発者
>Sosuke Ichihashi

> [![Sosuke Ichihashi](https://img.shields.io/badge/Sosuke_Ichihashi-black?logo=googlescholar&logoColor=white)](https://sosuke-ichihashi.com/)  
[![@sosucat](https://img.shields.io/badge/@sosucat-black?logo=github&logoColor=white)](https://github.com/sosucat)  
[![@RefreshSource](https://img.shields.io/badge/@RefreshSource-black?logo=x&logoColor=white)](https://x.com/refreshsource)

## 論文の引用方法
> 本プロジェクト **sbl-optimizer** を研究や制作に活用された場合は、以下の文献を引用してください：

* Sosuke Ichihashi, Noura Howell, and HyunJoo Oh. 2025.\
Swell by Light: An Approachable Technique for Freeform Raised Textures.\
In Proceedings of the Nineteenth International Conference on Tangible, Embedded, and Embodied Interaction (TEI '25). Association for Computing Machinery, New York, NY, USA, Article 45, 1–16. https://doi.org/10.1145/3689050.3704420

```bibtex
@inproceedings{10.1145/3689050.3704420,
author = {Ichihashi, Sosuke and Howell, Noura and Oh, HyunJoo},
title = {Swell by Light: An Approachable Technique for Freeform Raised Textures},
year = {2025},
isbn = {9798400711978},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3689050.3704420},
doi = {10.1145/3689050.3704420},
booktitle = {Proceedings of the Nineteenth International Conference on Tangible, Embedded, and Embodied Interaction},
articleno = {45},
numpages = {16},
keywords = {2.5D fabrication, Personal fabrication, tactile rendering},
location = {Bordeaux / Talence, France},
series = {TEI '25}
}
