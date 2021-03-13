# 三维小物体重建效果

## 重建效果展示
<style>
table th:first-of-type {
    width: 33%;
}
table th:nth-of-type(2) {
    width: 33%;
}
table th:nth-of-type(3) {
    width: 33%;
}
</style>
|物体|前|后|
|:-:|:-:|:-:|
|![](./bird1.png)|![](./bird6.png)|![](./bird9.png)|
|![](./cat1.png)|![](./cat2.png)|![](./cat3.png)|
||![](./frog1.png)|![](./frog2.png)|


## 主观效果对比
|自研|友商A|友商B|
|:-:|:-:|:-:|
|![](./bird2.png)|![](./bird3.png)|![](./bird4.png)|
|![](./bird6.png)|![](./bird7.png)|![](./bird8.png)|

## 客观评测
使用3D打印作为真值，计算的平均误差5.5mm，重建结果(黄色)与真值(蓝色)配准后点云如下图  
<style>
table th:first-of-type {
    width: 25%;
}
table th:nth-of-type(2) {
    width: 25%;
}
table th:nth-of-type(3) {
    width: 50%;
}
</style>
|打印模型|打印结果|重建对比|
|:-:|:-:|:-:|
|![](./cat0.png)|![](./cat1.png)|![](./cattar.png)|
