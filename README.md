# Milestones 1

Milestones ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Full Time Program khususnya pada Phase 1 dalam konsep Supervised Learning.

# Dataset

Dataset yang digunakan merupakan dataset dari pengguna credit card yang digunakan untuk memprediksi kemungkinan terjadinya gagal bayar di bulan berikutnya. Dataset di dapat dari Google `BigQuery`, atau dapat dilihat menggunakan link [berikut](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=ml_datasets&t=credit_card_default&page=table&project=husain-ftds-366112&ws=!1m5!1m4!4m3!1sbigquery-public-data!2sml_datasets!3scredit_card_default). Dengan kriteria query yang digunakan sebagai berikut: `SELECT limit_balance, sex, education_level, marital_status, age, pay_0, pay_2, pay_3, pay_4, pay_5, pay_6, bill_amt_1, bill_amt_2, bill_amt_3, bill_amt_4, bill_amt_5, bill_amt_6, pay_amt_1, pay_amt_2, pay_amt_3, pay_amt_4, pay_amt_5, pay_amt_6, default_payment_next_month FROMbigquery-public-data.ml_datasets.credit_card_defaultlimit 31984;`.

# Objectives

Milestones 1 ini dibuat guna mengevaluasi Pembelajaran Phase 1 dalam konsep Supervised Learning sebagai berikut:

- Mampu memahami konsep supervised learning
- Mampu mempersiapkan data untuk digunakan dalam model supervised learning
- Mampu mengimplementasikan supervised learning dengan data yang diberikan
- Mampu melakukan evaluasi model
- Mampu melakukan model tuning
