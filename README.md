# MLOPs-Production-Ready-Deep-Learning-Project



## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 


### How to Setup NVIDIA GPU For Deep Learning:

 - [Video Link](https://youtu.be/nATRPPZ5dGE?si=Xzv7uKEdW9yKODTS)


- [Project Youtube Playlist Link](https://youtube.com/playlist?list=PLkz_y24mlSJbaIL1wDOul5g45E6S8k-3P&si=zFK0GuM7MfwdKM6x)


- [Data Link](https://drive.google.com/file/d/1z0mreUtRmR-P-magILsDR3T7M6IkGXtY/view?usp=sharing)

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag