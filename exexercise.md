**演習問題1.1** \
Accuracy, Precison, Recallの定義は以下の通りである：
```math
\begin{gather}
\text{Accuracy} = \frac{TN + TP}{TN + TP + FN + FP} \\
\text{Precision} = \frac{TP}{FP + TP} \\
\text{Recall} = \frac{TP}{TP + FN}
\end{gather}
```
$\forall n \in \mathbb{N}$として, TP = 1, FP = FN = n, TN = $n^2$と与えれば, 
n→∞の極限を取ると, accuray が 1 で precition と recall が 0 に収束する.  すなわち, positive なデータが少ない場合, 題意を満たす例を構成することができる. 

