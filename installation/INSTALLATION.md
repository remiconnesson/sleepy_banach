On a UNIX machine, preferably Ubuntu 18.04

```
git clone https://github.com/remiconnesson/sleepy_banach.git 
cd sleepy_banach

conda create -n sleepy_banach --file conda_reqs.txt
conda activate sleepy_banach 
pip install pip_reqs.txt

chmox +x install.sh
./install.sh

python -m ipykernel install --user --name=sleepy_banach

python tests/test_install.py
```

If the result of the test is `yes` installation is successful.

Now open jupyter notebook, and attempt to run `tests/test_jupyter.ipynb` using `sleepy_banach` kernel.

Please kindly proceed with the file called 'REPRODUCIBILITY.md'


