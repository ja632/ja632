# part_b 講解
**題目:**

run experiments with different size values: 1000, 10000, 100000, and 1000000. Use the results to explain the difference between O(n log n) and O(n 2 ). Put your results and explanation
# 介紹**時間複雜度 (Time Complexity)**
## 2.1 big-o的求法
-   須算出每一段的功能的執行次數
-   將所有執行次數加總起來後
- 求出此演算法的時間複雜度 ── `Big-O`
## 2.2 difference between O(n log n) and O(n 2 )
C++ 函式庫``#include<algorithm>``裡面的sort() function 時間複雜度是O(n log n)，而我們自己寫的insertion sort()時間複雜度是O(n^2)，分別把n=1000、n=10000、n=100000、n=1000000，就可以大概知道當n愈大時O(n log n)的時間複雜度會遠小於
O(n^2)。
# execute result
![image_name](https://github.com/ja632/ja632/blob/main/result.png)
