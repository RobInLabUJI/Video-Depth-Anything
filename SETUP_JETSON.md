Download wheels from [https://pypi.jetson-ai-lab.io/jp6/cu126](https://pypi.jetson-ai-lab.io/jp6/cu126)

* torch-2.8.0
* torchvision-0.23.0
* triton-3.4.0
* xformers-0.0.32+8ed0992.d20250724

```
python -m venv vda
source vda/bin/activate
```

```
python -m pip install --upgrade pip
python -m pip install numpy==1.24.0
pip install torch-2.8.0-cp310-cp310-linux_aarch64.whl \
            torchvision-0.23.0-cp310-cp310-linux_aarch64.whl \
            triton-3.4.0-cp310-cp310-linux_aarch64.whl \
            xformers-0.0.32+8ed0992.d20250724-cp39-abi3-linux_aarch64.whl
```

Install Decord from [https://github.com/dmlc/decord](https://github.com/dmlc/decord)

```
pip install -r requirements.txt
```

