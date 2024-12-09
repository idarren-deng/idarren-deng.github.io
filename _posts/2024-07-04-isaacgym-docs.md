---
title: 'Isaac Gym’s Documentation'
date: 2024-07-04
permalink: /posts/2024/07/IsaacGym-Docs/
tags:
  - IsaacGym
---

Isaac Gym is NVIDIA’s prototype physics simulation environment for end-to-end GPU accelerated reinforcement learning research.

Prerequisites
---
Ubuntu 18.04, or 20.04.<br>
Python 3.6, 3.7, or 3.8<br>
Minimum recommended NVIDIA driver version: 470.74 (470 or above required)<br>
Minimum required hardware: NVIDIA Pascal or later GPU with at least 8gb of VRAM<br>

Isaac Gym - Download Archive
---
<p style="text-decoration:underline;"><a href="https://developer.nvidia.com/isaac-gym-preview-4">Isaac Gym - Ubuntu Linux 18.04 / 20.04 Preview 4 release</a></p>

Documentation
---
Here is the instruction docs found in the docs folder of offical Download Archive.
<p style="text-decoration:underline;"><a href="/docs/isaacgym_docs/index.html">Local Isaac Gym’s Documentation</a></p>

Notes
---
For anyone trying to set a conda environment up to add/remove LD_LIBRARY_PATH on activation/deactivation.

1. Activate the conda environment
2. Create files that are used/checked during activation/deactivation.
```
cd $CONDA_PREFIX
mkdir -p ./etc/conda/activate.d
mkdir -p ./etc/conda/deactivate.d
touch ./etc/conda/activate.d/env_vars.sh
touch ./etc/conda/deactivate.d/env_vars.sh
```
3. Edit ./etc/conda/activate.d/env_vars.sh as follows:
```
export ORIG_LD_LIBRARY_PATH=$LD_LIBRARY_PATH
export LD_LIBRARY_PATH=$CONDA_PREFIX/lib:$LD_LIBRARY_PATH
```
4. Edit ./etc/conda/deactivate.d/env_vars.sh as follows:
```
export LD_LIBRARY_PATH=$ORIG_LD_LIBRARY_PATH
```
Then, when you conda activate env_name it will add $CONDA_PREFIX/lib to LD_LIBRARY_PATH and when you conda deactivate it will return the LD_LIBRARY_PATH to what it was before activation.
