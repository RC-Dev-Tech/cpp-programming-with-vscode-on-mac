# ![](https://drive.google.com/uc?id=10INx5_pkhMcYRdx_OO4rXNXxcsvPtBYq) 如何在MacOS上使用VSCode去編譯C++

## 安裝 VSCode
- 進入 VSCode 官網[下載](https://code.visualstudio.com/) <br>
  ![](https://drive.google.com/uc?id=1gZ61xnfWpqUg1iJQi6tDvK4KuCrK5d91)
- 開啟 VSCode 選擇 Extenion <br>
  ![](https://drive.google.com/uc?id=10WqmHhcyj8dOZCbPz1tQ4ZYApt1p1_Vz)
- 安裝 C/C++ <br>
  ![](https://drive.google.com/uc?id=1z-EOAntNa9mg_8syyvIubaq-pPLPv2DC)
- 安裝 C++ Intellisense <br>
  ![](https://drive.google.com/uc?id=1JFgVmlogyHYbCWtde7v4fCzj-pufZl9o)


## 開始撰寫 C/C++
`Exsample Code.`
```c++
#include <iostream>
using namespace std;

int main()
{
    cout << "hello world !!" << endl;
    return 0;
}
```

## 編譯專案
- 按下 <font color=#4169e1>Run adn Debug</font> 按鈕，並且選擇 <font color=#4169e1>Clang++</font> 的建置方式 <br>
  ![](https://drive.google.com/uc?id=1hhmOE6ttKAx4AGdhXPo9POkULMmpCUzc)
- 可以看到成功後的log. <br>
  ![](https://drive.google.com/uc?id=1tHWVpl0JaQX-1sS6k56ET5G3n-hQPyM4)
## 中斷除錯
- 設立中斷點，檢視中斷當下的變數資料. <br>
![](https://drive.google.com/uc?id=1H_KzIV95LrBaKQJB0ykxHdfQRLlA9fGM)

## 參考文件
https://code.visualstudio.com/docs/languages/cpp
