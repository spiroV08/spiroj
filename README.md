# spiroj
pip install polars pandas scikit-learn matplotlib
import polars as pl
train_df = pl.read_csv("training.csv.gz")
test_df = pl.read_csv("testing.csv.gz")
print(train_df.head())
print(train_df.shape)
print(test_df.shape)
