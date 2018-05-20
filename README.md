Inverse Soft Q-Learning
=======================

Learn an agent's beliefs about the dynamics of the environment from their control demonstrations.

Usage
-----

Install Python dependencies with the [pip](https://pip.pypa.io/en/stable/installing/) package
manager using

```
pip install -r requirements.txt
```

Install [gym](https://github.com/openai/gym) and replace `gym/envs/box2d/lunar_lander.py` with `isql/lunar_lander.py`.

Install [baselines](https://github.com/openai/baselines) and replace `baselines/baselines/deepq/{build_graph|simple}.py` with `isql/{build_graph|simple}.py`.

Extract [this zip file](https://drive.google.com/file/d/1z-SzHf5T2Ynpj-5dwVcB4TCNEehleR9K/view?usp=sharing) into `isql/`.

Questions and comments
----------------------

Please contact the author at `sgr [at] berkeley [dot] edu` if you have questions or find bugs.

Citation
--------
If you find this software useful in your work, we kindly request that you cite the following [paper](https://arxiv.org/abs/):

```
@InProceedings{Reddy/etal/18b,
  title={Where Do You Think You're Going?: Inferring Beliefs about Dynamics from Behavior},
  author={Reddy, Siddharth and Dragan, Anca D. and Levine, Sergey},
  booktitle={Arxiv },
  year={2018},
  url={https://arxiv.org/abs/}
}
```