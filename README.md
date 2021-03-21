## Tree
scikit-learnだけで決定木を可視化できる

```python
from sklearn import tree

# モデルの作成
clf = tree.DecisionTreeClassifier(random_state=42)

# 学習
clf = clf.fit(X, y)

# 決定木の表示
tree.plot_tree(clf)
```

### 情報元のツイート
https://twitter.com/arts_lib/status/1373274504919617538?s=19

### 公式ドキュメント
https://scikit-learn.org/stable/modules/tree.html
