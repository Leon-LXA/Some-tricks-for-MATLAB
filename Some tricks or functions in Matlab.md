# Some tricks or functions in Matlab

## 绘制图像

```matlab
grid on 			图像栅格化
scatter(X,Y,S,C,'filled')				实心某色某大小XY散点图
ylim([-5,5])							图像显示坐标范围
plot(X,Y,'Color',[0 1.0 0],'LineWidth',2) 画线段图

uisetcolor						可以选取颜色获知RGB参数
推荐橙色点蓝色线
plot(x,y,'color',[0.3020 0.7451 0.9333],'linewidth',2);
hold on;
scatter(lgf,Au,20,[1.0000 0.4118 0.1608],'filled');
```



