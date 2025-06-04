# Prediction of Market Capitalization using Machine Learning Python

## Repository Outline
Repository ini terdiri dari file:
```
1. README.md - Penjelasan gambaran umum project
2. notebook.ipynb - Notebook yang berisi work flow dari pemahaman data, pembersihan data, penyiapan data, penyiapan pipeline dan model, modeling, dan simpulan.
```

## Problem Background
`Market Capitalization` merepresentasikan nilai pasar saham dibandingkan dengan jumlah saham yang beredar. Nilai `Market Capitalization` biasanya digunakan investor untuk melihat ukuran perusahaan di pasar, yang kemudian jika dibandingkan kembali dengan kinerja keuangan, bisa menjadi dasar dalam pengambilan keputusan untuk berinvestasi atau tidak. `Market Capitalization` dapat dikategorikan menjadi 3 yaitu perusahaan dengan Large-cap atau nilai kapitalisasi di atas $10,000 juta, perusahaan dengan Med-cap atau nilai kapitalisasi di atas $3,000 juta s.d. $10,000 juta, dan Low-cap atau nilai kapitalisasi di bawah $3,000 juta. Large-cap merepresentasikan perusahaan yang sudah mapan, _well-known_, dan umumnya memberikan dividen rutin para investornya. Med-cap merepresentasikan perusahaan yang sudah cukup _established_, tapi tidak semapan atau sestabil Large-cap. Risiko berinvestasi di perusahaan Med-cappun lebih tinggi dibandingkan berinvestasi di Large-cap. Terakhir, Low-cap biasanya adalah perusahaan-perusahaan baru yang mulai merintis, skalanya mungkin masih kecil dibandingkan kedua perusahaan lain.

## Project Output
Keluaran dari proyek ini adalah hasil prediksi `Market Capitalization` yang dapat dicoba pada platform HuggingFace.

## Data
Proyek ini menggunakan dataset dari [Kaggle](https://www.kaggle.com/datasets/shriyashjagtap/esg-and-financial-performance-dataset/data). Data berisi tentang informasi keuangan dan kinerja ESG (_Environmental_, _Social_, dan _Governance_) pada 11.000 perusahaan dengan 9 jenis industri dan 7 wilayah sejak tahun 2015 s.d. 2025.

## Method
Proyek ini mengenai machine learning sehingga metode yang dipakai adalah model supervised learning - regression dengan model `RandomForest`

## Stacks
Bahasa pemrograman: Python

Tools: VSCode, Streamlit, HuggingFace

Library: pandas, numpy, scikit-learn, matplotlib, seaborn, scipy, dan pickle

## Reference
Hasil analisis pada proyek ini berdasarkan referensi:
- [Market Capitalization Bagian 1](https://www.investopedia.com/terms/m/marketcapitalization.asp)
- [Market Capitalization Bagian 2](https://www.merrilledge.com/article/company-size-why-market-capitalization-matters-ose)
- [Carbon Emissions](https://pwypindonesia.org/id/urgensi-keterbukaan-data-emisi-gas-rumah-kaca-pertambangan-batubara-dalam-upaya-memerangi-krisis-iklim/)
- [R2 Score Interpretation](https://towardsdatascience.com/negative-r2-where-did-you-go-wrong-9d4f2aa84cfb/)
- [Residual Plot Interpretation](https://www.qualtrics.com/support/stats-iq/analyses/regression-guides/interpreting-residual-plots-improve-regression/)

Deployment:
[HuggingFace](https://huggingface.co/spaces/neilaism/predict-marketcap)

Presentation Deck:
[Canva](https://www.canva.com/design/DAGoPS8fl4g/uqo3NQD-vd2dD1Tobrq8hw/view?utm_content=DAGoPS8fl4g&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h70e9d21795)

---
