# sbl-optimizer-colab
Google Colab notebook to try out sbl-optimizer. sbl-optimizer optimizes print pattern for [Swell by Light](https://sites.gatech.edu/futurefeelings/2025/03/07/swell-by-light-tei-25/).

[![PyPI version](https://badge.fury.io/py/sbl-optimizer.svg)](https://badge.fury.io/py/sbl-optimizer)
[![GitHub](https://img.shields.io/badge/GitHub_repo-black?logo=github)](https://github.com/sosucat/sbl-optimizer)

[![Homepage](https://img.shields.io/badge/🔗_Homepage-black)](https://sites.gatech.edu/futurefeelings/2025/03/07/swell-by-light-tei-25/)
[![Author](https://img.shields.io/badge/Author-black?logo=googlescholar&logoColor=white)](https://sosuke-ichihashi.com/)
[![Research paper](https://img.shields.io/badge/Research_Paper-black?logo=acm)](https://doi.org/10.1145/3689050.3704420)
[![Fabrication](https://img.shields.io/badge/🔗_Fabrication-black)](https://sites.gatech.edu/futurefeelings/2025/07/23/make-puffy-patterns-with-light/)
[![Watch fabrication demo on YouTube](https://img.shields.io/badge/Fabrication-750014?logo=youtube)](https://youtu.be/LomVS_jHxl0?feature=shared)

Welcome to **sbl-optimizer**, a friendly tool that turns your images into printable patterns for 2.5D raised textures!  
Anyone—even with zero coding experience—can upload a picture, run cells, and get an optimized pattern you can print, shine light, and watch pop up like magic.

![A printed pattern's shades change as the optimization progresses, and the resulting temperature distribution gets closer to the intended pattern.](https://sites.gatech.edu/futurefeelings/files/2025/03/opt_step.gif)

Optimization of the printed pattern results in a uniform temperature pattern (right) closely matching the original pattern (left). In this example, the leaves are over-heated while the stems are under-heated before the optimization.
As the iteration number goes up, the leaves' temperature goes down while the stems' goes up, resulting in a more uniform temperature distribution.


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
