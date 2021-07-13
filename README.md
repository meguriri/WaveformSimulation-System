# WaveformSimulation System

## 介绍

本项目为一款波形发生器仿真软件，基于Echarts API实现，能够配置包括：常量、脉冲、斜坡、双斜坡、阶梯、阶跃、正弦等信号波形，并能生成波形仿真数据。要求系统设计考虑日后随时增加不同新的波形。该系统能够完成以下功能：

1. 采用图形化界面配置波形参数；
2. 可以配置波形组合；
3. 能够绘制随时间变换的波形曲线；
4. 波形配置信息能够保存到文件；
5. 能够从文件中读取波形配置信息，进行修改。

## 项目目录结构

```
waveform-simulation-system
├─ js
│  ├─ FileSaver.js    //保存文件功能js文件
│  └─ wave.json		  //波形数据json文件
├─ newWave.html		  //界面的html文件
└─ README.md		  //项目说明文件
```

## 波形种类

### 常量(const)

1. 开始时间 firstTime

2. 结束时间 secondTime

3. 幅值 amp

### 脉冲(pulse)

1. 开始时间 firstTime

2. 结束时间 secondTime

3. 幅值 amp


### 斜坡(slope)

1. 开始时间 firstTime

2. 结束时间 secondTime

3. 开始幅值 firstamp

4. 结束幅值 secondamp


### 双斜坡(dualslop)

1. 第一个开始时间 ffirstTime

2. 第一个结束时间 fsecondTime

3. 第一个开始幅值 ffamp

4. 第一个结束幅值 fsamp

5. 第二个开始时间 sfirstTime

6. 第二个结束时间 ssecondTime

7. 第二个开始幅值 sfamp

8. 第二个结束幅值 ssamp

   

### 阶梯(step)

1. 开始时间 firstTime
2. 结束时间 secondTime
3. 第一次幅值 amp
4. 阶梯高度 stepH
5. 阶梯持续时间 stepDur
6. 阶梯个数 stepNum

### 阶跃(pstep)

1. 开始时间 firstTime
2. 结束时间 secondTime
3. 第一次幅值 amp
4. 阶跃高度 stepH
5. 阶跃持续时间 stepDur
6. 阶跃个数 stepNum

### 正弦(sin)

1. 开始时间 firstTime
2. 结束时间 secondTime
3. 振幅 amp
4. 角速度 av
5. 初相 diff

