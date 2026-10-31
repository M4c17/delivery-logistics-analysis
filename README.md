# Teslimat Analizi ve Sınıflandırma | Delivery Logistics Analysis

[Notebook](notebook.ipynb) · [Kaggle](https://www.kaggle.com/code/enesfurkanmacit/delivery-logistics-eda-classification-analysis)

## Türkçe

Teslimat verilerinin dağılımları, araç ve paket türleri incelenir; teslimat puanı grupları LightGBM ve XGBoost ile sınıflandırılır. Notebook, veri hazırlama, görselleştirme ve sınıf bazında precision, recall ve F1 değerlendirmelerini içerir. LightGBM test kümesinde 0,74 doğruluk sağlarken orta sınıf için recall 0,07'dir; bu nedenle genel doğruluk tek başına yeterli değildir.

## English

Exploratory analysis of delivery data followed by LightGBM and XGBoost classification of delivery rating groups. The notebook reports class-level precision, recall and F1. LightGBM achieved 0.74 accuracy on the test split, but recall for the average class was 0.07, highlighting a limitation of overall accuracy.

## Çalıştırma / Reproduction

Python, pandas, NumPy, matplotlib, seaborn, plotly, scikit-learn, LightGBM and XGBoost are used. Download the dataset linked in the [Kaggle notebook](https://www.kaggle.com/code/enesfurkanmacit/delivery-logistics-eda-classification-analysis) and adapt the Kaggle input path for local use.
