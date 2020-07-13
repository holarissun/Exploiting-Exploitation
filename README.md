# Zeroth-Order Supervised Policy Improvement

This repo contains the PyTorch implementation of the Zeroth-Order Supervised Policy Improvement (ZOSPI) [paper](https://arxiv.org/abs/2006.06600). 

The ZOSPI method is tested on [MuJoCo](http://www.mujoco.org/) continuous control tasks in [OpenAI gym](https://github.com/openai/gym). 
Our implementation is based on the [TD3](https://github.com/sfujim/TD3) code implementation. 

### Usage

The paper results can be reproduced by running the jupyter notebooks, or running the corresponding files directly by running, e.g.,

```
python main.py
```

To run the code with different environments or methods, users can revise the args *--env_name* and *--policy* (from 'SPI', 'TD3', 'DDPG', etc.).

### Bibtex

```
@article{sun2020zeroth,
  title={Zeroth-Order Supervised Policy Improvement},
  author={Sun, Hao and Xu, Ziping and Song, Yuhang and Fang, Meng and Xiong, Jiechao and Dai, Bo and Zhang, Zhengyou and Zhou, Bolei},
  journal={arXiv preprint arXiv:2006.06600},
  year={2020}
}
```
