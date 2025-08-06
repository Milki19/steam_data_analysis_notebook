# Steam Dataset Analiza – Databricks Notebook

Ovaj repozitorijum sadrži Jupyter notebook kreiran u **Databricks okruženju** za analizu podataka sa Steam platforme. Podaci su preuzeti u realnom vremenu pomoću **Kafka stream-a** i prethodno procesirani u zasebnom Java projektu.

---

## Korišćene tehnologije

- **Databricks (Community Edition)**
- **Apache Spark (PySpark)**
- **Kafka (za ingest podataka)**
- **Pandas / Matplotlib / PySpark SQL**
- `.ipynb` format noteboooka

---

## Opis analize

U okviru ovog projekta izvršene su sledeće analize nad datasetom o Steam igrama:

- Analiza distribucije žanrova i ocena
- Korelacija između broja recenzija i ocena
- Identifikacija popularnih i nepopularnih kategorija
- Vizualizacija vremenskih trendova i korisničkog interesovanja
- Upotreba Spark SQL za agregaciju i filtriranje

---

## Notebook

Notebook je dostupan u `.ipynb` formatu i može se otvoriti putem:
- Jupyter Notebook
- Google Colab
- Databricks

Možeš direktno pogledati sadržaj ovde:  
📎 [`Veliki podaci.ipynb`](Veliki%20podaci.ipynb)

---

## 🚀 Kako pokrenuti

1. Kloniraj repozitorijum:
```bash
git clone https://github.com/Milki19/steam-data-analysis-notebook.git
```

2. Otvori notebook u Jupyter/Colab/Databricks

---

