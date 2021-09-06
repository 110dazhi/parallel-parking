# 侧方停车
```
 python main_autopark.py --x_start 0 --y_start 90 --psi_start 0 --parking 7
 ```
 `--x_start 0 --y_start 90` 定义汽车初始位置.

 `--psi_start 0`定义汽车初始车头朝向.

 `--parking 7`定义汽车选定的停车位

 # 算法
 1. A* 目前只有一个，挖个坑，后续加一个hybird A*。
 2. MPC

 # 参考
>https://en.wikipedia.org/wiki/A*_search_algorithm

>https://github.com/Pandas-Team/Automatic-Parking

>https://en.wikipedia.org/wiki/MPC
