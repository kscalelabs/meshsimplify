# meshsimplify

Mesh Simplification and Conversion

```
git clone https://github.com/kscalelabs/meshsimplify.git && cd meshsimplify
conda create -y -n meshsimplify python=3.8 && conda activate meshsimplify
pip install -r requirements.txt
```

```
python run.py \
    --input_dir /path/to/urdf_dir \
    --output_dir /path/to/urdf_dir_new \
    --output_format obj    
```