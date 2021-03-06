# 全彩点阵魔块

RGB

![](./images/11_04.png)


此模块是8x8的全彩点阵屏，可以单独控制任意一个点的颜色或者整个屏幕的颜色。支持点阵屏之间串接，无缝组成16x16或者8x32等点阵屏，让显示效果更加丰富。我们提供可视化的点阵屏图形编辑器，可以直接在编辑器上作画或者导入简单图片，最终在全彩点阵屏显示出来。


## 详细介绍

![](./images/11_03.png)

## 参数介绍

- 支持电压： 3V-5V
- 尺寸：56mm X 24mm X 16mm
- 接口：PH2.0 4PIN端子 ，引脚服从GVAB排布
- 像素：8x8全彩



对应Makecode编程界面：

Makecode在线地址：https://makecode.microbit.org/beta#editor

加载Powerbrick插件地址：https://github.com/KittenBot/pxt-powerbrick


## 使用注意事项

- 点阵屏上有两个接口，输入和输出，单个使用时，输入接口与Armourbit连接。
- 多个点阵屏之间拼接，前一个点阵屏的输出口，与下一个点阵屏的输入口连接，最终组成一个大点阵屏。
- 彩色点阵屏之间拼接，在电池盒供电状态下，最多拼接4个。如需接更多，需外接电源。可适当降低点阵亮度（通常用亮度10已足够），以此减少电流。
- 长时间使用彩色点阵屏请注意模块散热。



## 编程介绍

### 全彩点阵屏彩虹编程

![](./images/11_01.png)

## 多屏拼接示例

![](./images/11_02.png)

