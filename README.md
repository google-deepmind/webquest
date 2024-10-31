## WebQuest

WebQuest is a multimodal benchmark focused on question answering based on the
contents of web UIs.


WebQuest is targeted to capture the scenarios where users navigate to different
websites to retrieve information relevant to a particular question. In contrast
with many question answering datasets which are based on information contained
in a single image/UI, WebQuest enhances the scope of the QA task by requiring
the combination of information from multiple distinct parts of UIs. Furthermore,
 WebQuest also contains questions spanning multiple related webpages and
websites.

WebQuest contains 3 categories of increasing difficulty:
* Single screen QA: Questions based on the contents of a single screen.
* Multi screen QA: Questions spanning multiple semantically related web pages.
For this task, the web pages are filtered such that all of them are required to
answer the question of interest
* Trace QA:  Questions about the entire sequence of screens viewed by the user
as they navigate the web with a particular goal.


## Paper

### [WebQuest: A Benchmark for Multimodal QA on Web Page Sequences](https://arxiv.org/abs/2409.13711)

This paper describes the WebQuest benchmark, data collection methodology and
evaluations of various proprietary and open source models on the dataset.

If you use or discuss this dataset in your work, please cite our paper:

```shell
@misc{wang2024webquestbenchmarkmultimodalqa,
      title={WebQuest: A Benchmark for Multimodal QA on Web Page Sequences},
      author={Maria Wang and Srinivas Sunkara and Gilles Baechler and Jason Lin and Yun Zhu and Fedir Zubach and Lei Shu and Jindong Chen},
      year={2024},
      eprint={2409.13711},
      archivePrefix={arXiv},
      primaryClass={cs.IR},
      url={https://arxiv.org/abs/2409.13711},
}
```

## Contact us

If you have a technical question regarding the dataset or publication, please
create an issue in this repository. Alternatively, you can reach out to us via
the correspondence details in the [paper](https://arxiv.org/abs/2409.13711).

## License and disclaimer

Copyright 2024 DeepMind Technologies Limited

All software is licensed under the Apache License, Version 2.0 (Apache 2.0);
you may not use this file except in compliance with the Apache 2.0 license.
You may obtain a copy of the Apache 2.0 license at:
https://www.apache.org/licenses/LICENSE-2.0

All other materials are licensed under the Creative Commons Attribution 4.0
International License (CC-BY). You may obtain a copy of the CC-BY license at:
https://creativecommons.org/licenses/by/4.0/legalcode

Unless required by applicable law or agreed to in writing, all software and
materials distributed here under the Apache 2.0 or CC-BY licenses are
distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
either express or implied. See the licenses for the specific language governing
permissions and limitations under those licenses.

This is not an official Google product.
