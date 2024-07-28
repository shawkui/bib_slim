## Bib Slim
[Online version](https://shawkui.github.io/tools/bib_slimmer.html)
* Purpose

    The slim.py script is a Python script that takes a bib file as input and outputs a slimmed version of the file. It has the following functions:
    - It **removes unnecessary fields** such as author, editor, timestamp, and url from the bib entries. 
    - It **reformats the booktitle/journal field** by replacing it with a formal name/abbreviation.

* How to Use

    To use this demo, follow these steps:

    1. Clone the repository containing the demo files.
    2. Run the slim.py script on your bib file to slim it.


*  Examples
   1. Before slimming the bib file:

           ```
           @inproceedings{dong2020adversarial,
           author = {Yinpeng Dong and
           Zhijie Deng and
           Tianyu Pang and
           Jun Zhu and
           Hang Su},
           bibsource = {dblp computer science bibliography, https://dblp.org},
           biburl = {https://dblp.org/rec/conf/nips/DongDP0020.bib},
           booktitle = {Advances in Neural Information Processing Systems 33: Annual Conference on Neural Information Processing Systems 2020, NeurIPS 2020, December
           6-12, 2020, virtual},
           editor = {Hugo Larochelle and
           Marc'Aurelio Ranzato and
           Raia Hadsell and
           Maria{-}Florina Balcan and
           Hsuan{-}Tien Lin},
           timestamp = {Tue, 19 Jan 2021 00:00:00 +0100},
           title = {Adversarial Distributional Training for Robust Deep Learning},
           url = {https://proceedings.neurips.cc/paper/2020/hash/5de8a36008b04a6167761fa19b61aa6c-Abstract.html},
           year = {2020}
           }
           ```

    2. After slim:

           ```
           @inproceedings{dong2020adversarial,
           title = {Adversarial Distributional Training for Robust Deep Learning},
           author = {Yinpeng Dong and Zhijie Deng and Tianyu Pang and Jun Zhu and Hang Su},
           booktitle = {NeurIPS 2020},
           year = {2020}
           }
           ```

       
* Other recommend resources
    * Rebiber: A tool for normalizing bibtex with official info: https://github.com/yuchenlin/rebiber
