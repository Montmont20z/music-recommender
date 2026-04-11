### Installation
Initialize virtual environment
make sure to use python 3.12
```bash
python3 -m venv .venv
```

# 2. Activate the environment
```bash
.\venv\Scripts\activate
```

# 3. Upgrade pip to ensure smooth installation
```bash
python -m pip install --upgrade pip
```

# 4. Install the specific libraries from your import list
```bash
pip install pandas numpy matplotlib scipy scikit-learn shap lime
```



### Dataset
##### LastFM & Spotify
```
curl http://mtg.upf.edu/static/datasets/last.fm/lastfm-dataset-1K.tar.gz
https://www.kaggle.com/code/vatsalmavani/music-recommendation-system-using-spotify-dataset/input
```


download lastfm-dataset-1K.tar.gz, then extract to `data/lastfm-dataset-1K/`
