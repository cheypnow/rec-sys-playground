# Recommending music using qdrant

## Setup
1. Download dataset https://www.kaggle.com/datasets/jorgeruizdev/ludwig-music-dataset-moods-and-subgenres 
2. Create venv
3. Install dependencies
```
python -m pip install -r requirements.txt
```
4. Install kernelspec
```
python -m ipykernel install --user --name qdrant_music_recs
```
5. Run container with qdrant
```
docker-compose up
```
6. Run jupyter and open notebook with installed kernel
7. Change paths to dataset