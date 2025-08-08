<p align="left">
🔤 <a href="#english">English</a> | 🇯🇵 <a href="#日本語">日本語</a>
</p>

---

## English

# **``🐐 sbl-optimizer``** Advanced Colab Notebook<br> Pattern Optimizer for [Swell by Light](https://sites.gatech.edu/futurefeelings/2025/03/07/swell-by-light-tei-25/)
[![Advanced Colab](https://img.shields.io/badge/Try_This_Notebook-black?logo=googlecolab)](https://colab.research.google.com/drive/1Df32_XEfXZwHhXW8_8GQt3X7Hf300CxG?usp=sharing)

[![License](https://img.shields.io/badge/license-MIT-750014)](LICENSE)
[![PyPI version](https://badge.fury.io/py/sbl-optimizer.svg)](https://badge.fury.io/py/sbl-optimizer)
[![GitHub](https://img.shields.io/badge/GitHub_repo-black?logo=github)](https://github.com/sosucat/sbl-optimizer)

[![Homepage](https://img.shields.io/badge/🔗_Homepage-black)](https://sites.gatech.edu/futurefeelings/2025/03/07/swell-by-light-tei-25/)
[![Author](https://img.shields.io/badge/Author-black?logo=googlescholar&logoColor=white)](https://sosuke-ichihashi.com/)
[![Research paper](https://img.shields.io/badge/Research_Paper-black?logo=acm)](https://doi.org/10.1145/3689050.3704420)
[![Fabrication](https://img.shields.io/badge/🔗_Fabrication-black)](https://sites.gatech.edu/futurefeelings/2025/07/23/make-puffy-patterns-with-light/)
[![Watch fabrication demo on YouTube](https://img.shields.io/badge/Fabrication-750014?logo=youtube)](https://youtu.be/LomVS_jHxl0?feature=shared)

Welcome to **sbl-optimizer**, a tool optimizing your pattern images for 2.5D texture fabrication!
**This notebook is an advanced version** walking through all the codes.
If you just want to use sbl-optimizer without minding the coding, check out the simplified Colab notebook:

[![Simpler Colab](https://img.shields.io/badge/Simpler_Colab_Notebook-black?logo=googlecolab)](https://github.com/sosucat/sbl-optimizer-colab-simple)

---


![A printed pattern's shades change as the optimization progresses, and the resulting temperature distribution gets closer to the intended pattern.](https://sites.gatech.edu/futurefeelings/files/2025/03/opt_step.gif)

Optimization of the printed pattern results in a uniform temperature distribution (right) closely matching the original pattern (left). In this example, the leaves are over-heated while the stems are under-heated before the optimization. As the iteration number goes up, the leaves' temperature goes down while the stems' goes up, resulting in a more uniform temperature distribution.

---


# Credits & License
## License
>This project is licensed under the [MIT License](LICENSE).


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

# ``🐐 sbl-optimizer`` 上級Colabノート<br>[Swell by Light](https://sites.gatech.edu/futurefeelings/2025/07/03/swell-by-light-tei-25-2/)用の模様最適化
[![Advanced Colab](https://img.shields.io/badge/このノートを開く-black?logo=googlecolab)](https://colab.research.google.com/drive/1Df32_XEfXZwHhXW8_8GQt3X7Hf300CxG?usp=sharing)

[![PyPI version](https://badge.fury.io/py/sbl-optimizer.svg)](https://badge.fury.io/py/sbl-optimizer)
[![sbl-optimizer](https://img.shields.io/badge/sbl--optimizer-black?logo=github)](https://github.com/sosucat/sbl-optimizer?tab=readme-ov-file#sbl-optimizer-%E6%97%A5%E6%9C%AC%E8%AA%9E)

[![Homepage](https://img.shields.io/badge/🔗_ホームベージ-black)](https://sites.gatech.edu/futurefeelings/2025/07/03/swell-by-light-tei-25-2/)
[![Author](https://img.shields.io/badge/著者サイト-black?logo=googlescholar&logoColor=white)](https://sosuke-ichihashi.com/)
[![Research paper](https://img.shields.io/badge/研究論文-black?logo=acm)](https://doi.org/10.1145/3689050.3704420)
[![Fabrication](https://img.shields.io/badge/🔗_作り方-black)](https://sites.gatech.edu/futurefeelings/2025/07/23/%e5%85%89%e3%81%a7%e3%83%87%e3%82%b3%e3%83%9c%e3%82%b3%e3%82%82%e3%82%88%e3%81%86%e3%82%92%e4%bd%9c%e3%82%8d%e3%81%86%ef%bc%81/)
[![Watch fabrication demo on YouTube](https://img.shields.io/badge/作り方-750014?logo=youtube)](https://youtu.be/LomVS_jHxl0?feature=shared)

**sbl-optimizer** は、Swell by Lightで画像に忠実なデコボコ模様を作るため、画像の濃淡を修正するソフトです。

**本ノートは上級者向け**なので、sbl-optimizerライブラリをPython環境で利用して模様画像を最適化する方法の詳細を理解できます。

**sbl-optimizerをパッと使いたいだけの方は、以下の簡易版をおすすめ**します。
簡易版では、プログラミングの知識がなくても、画像をアップロードしてセルを実行するだけで、最適化された画像を作ることができます。できあがった画像を印刷し、光を当てると、元画像の模様と同じようなデコボコ模様ができあがります。

[![Simpler Colab](https://img.shields.io/badge/簡易版ノートを開く-black?logo=googlecolab)](https://colab.research.google.com/drive/15zYmaNvh88jztUcqpzwLXtT4YMRk2i1G?usp=sharing)

---

![最適化によって印刷パターンの濃淡が変化し、温度分布が意図したデザインに近づいていく様子](https://sites.gatech.edu/futurefeelings/files/2025/03/opt_step.gif)

画像の模様の濃淡を最適化することで、画像の模様（左）に近い、均一な温度分布（右）になり、画像に近いきれいなデコボコ模様ができます。
この例では、最適化前（iteration: 0）は葉の部分が熱くなりすぎている一方で、茎の部分は加熱不足の状態でした。
最適化が進むにつれて、葉の温度は下がり、茎の温度は上昇していき、結果としてより均一な温度分布が実現されています。

---

# クレジットとライセンス

## ライセンス
>このプロジェクトは [MIT ライセンス](LICENSE) のもとで公開されています。

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
