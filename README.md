# Projet de Web Scraping for GO AI CORPORATION

## Description
Ce projet démontre le web scraping à partir de [ https://www.webonary.org/moore/ ]. L'objectif est d'extraire [ les phrases en moorée et leurs correspondances en francais ].

## Fichiers
- `datas.json` : Contient les données extraites au format JSON.
- `web_scraping_moore.ipynb` : Jupyter Notebook avec le code de web scraping.
- `data_final.csv` : Contient les données du site [ https://www.webonary.org/moore/ ].
- `data_f.csv` : Autre source.

```json
python import json

with open("datas.json", "r", encoding="utf-8") as f: data = json.load(f)

for i in range(3): # Print the first 3 elements print(data[i])
```

## Auteur
[ PAFADNAM Ibrahim ]
