# Chest-Disease-Classification-from-Chest-CT-Scan-Image


 [Data link](https://drive.google.com/file/d/1n3se-pYdtAmu2j7_pC8rEwh6Yt-4W25E/view?usp=sharing)



## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

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

## Mlflow dagshub connection uri

``` bash
MLFLOW_TRACKING_URI=https://dagshub.com/ksusheela/MLFlow_Experiment.mlflow \
MLFLOW_TRACKING_USERNAME=ksusheela \
MLFLOW_TRACKING_PASSWORD=b21b4d2213fd4f7a4a7cc3e2855c87ad9b6c7c61 \
python script.py
```
## RUN from bash terminal

``` bash
export MLFLOW_TRACKING_URI=https://dagshub.com/ksusheela/MLFlow_Experiment.mlflow 

export MLFLOW_TRACKING_USERNAME=ksusheela 

export MLFLOW_TRACKING_PASSWORD=b21b4d2213fd4f7a4a7cc3e2855c87ad9b6c7c61 

```
