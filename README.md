# Shor-cut-CNN CIFAR-10 圖像分類

參照ResNet18 模型來對 CIFAR-10 數據集進行圖像分類，通過使用殘差模組來緩解深層網絡的退化問題。

## 專案結構

- `data/`：存放 CIFAR-10 數據集。
- `model/`：存放 仿ResNet18 模型的定義和訓練腳本。
- `notebooks/`：存放 Colab 文件。
- `README.md`：專案的介紹文件。

文件說明
train.py
此文件包含了模型的訓練代碼。通過調用 train() 函數來進行模型的訓練。

test.py
此文件包含了模型的測試代碼。通過調用 test() 函數來進行模型的評估。

visualize.py
此文件包含了顯示測試結果的代碼。通過調用 imshow() 函數來顯示測試圖像和預測結果。

結果
在 CIFAR-10 數據集上的測試結果如下：

總準確率：68.68%
各類別準確率：
plane: 75.7 %
car  : 84.8 %
bird : 64.3 %
cat  : 44.7 %
deer : 53.3 %
dog  : 57.9 %
frog : 77.6 %
horse: 79.1 %
ship : 74.9 %
truck: 74.5 %
