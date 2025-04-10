# Conda-Tutorial
This is a conda tutorial repository.

- To deactivate the environment:
Just run:

```bash
conda deactivate
```
This takes you back to the base environment (or your system shell if you're not in base).

- To delete the environment (foundationpose_ros) entirely:
If you're sure you don’t want it anymore:

```bash
conda remove --name foundationpose_ros --all -y
```
This will completely remove the environment and all packages installed inside it.

- Optional: Check environments (to verify it's gone):
```bash
conda env list
# Or
conda info --envs
```
This shows all your environments and their locations.


