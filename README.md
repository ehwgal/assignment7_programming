ASSIGNMENT 7 PROGRAMMING
----------------------------
*by Ellemijn Galjaard*

**Sidenote**: *Unfortunately, this project is not (yet) finished (the model is in the process of being trained and is not tested in any manner). This is because it already took a incredibly long time to get to where the notebook is now. I might add additional commits to evaluate the model in the future, but they won't count towards this assignment.*

This project uses a Portuguese [open-source TTS dataset](https://github.com/Edresson/TTS-Portuguese-Corpus) (please refer to the following [LICENSE](https://github.com/Edresson/TTS-Portuguese-Corpus/blob/master/LICENSE)) to train a [COQUI-based](https://github.com/coqui-ai/TTS) TTS model (please refer to the following [LICENSE](https://github.com/coqui-ai/TTS/blob/dev/LICENSE.txt)). This project is a school project and not intended for commercial use.

**Please note that no ``requirements.txt`` file is added as this file is pulled and executed within ``run_model.ipynb``.**

STEPS TO RUN THIS PROJECT
-----------------------------

The notebook file is meant to run in a Google Colab environment

1. Please download or clone this project to your Google Colab.

2. Make sure your directory/file structure on your Google Drive is set up in the following way:
```
├── content    # root directory                     
│   ├── drive
│   ├────── MyDrive
│   └────────── assignment7_programming  # directory downloaded from this GitHub project
```

3. Execute **``run_model.ipynb``**.

**Please note that running the notebook will download quite a large amount of data onto your computer. Downloading and unzipping this data might take a while.**

