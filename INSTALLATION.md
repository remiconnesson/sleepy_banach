On a UNIX machine, preferably Ubuntu 18.04

```
git clone https://github.com/remiconnesson/sleepy_banach/
cd sleepy_banach

conda create -n sleepy_banach --file conda_req.txt
conda activate sleepy_banach 
pip install pip_req.txt

chmox +x install.sh
./install.sh

python tests/test_install.py
```

If the result of the test is `yes` installation is successful.
Please kindly proceed with the file called 'REPRODUCIBILITY.md'


