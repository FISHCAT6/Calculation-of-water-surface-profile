# Calculation-of-water-surface-profile
依托Matlab自研溢洪道水面线计算算法
## **1.开发背景**

  现阶段河流水动力学计算软件主要以HEC-RAS和MIKE 21为主。两者均为大型水利工程计算软件，无稳定汉化版本且上手门槛较高。固开发此软件供广大工程设计人员使用，在处理小型水利工程时界面简单，运行速度快，且不需要专业培训。

## **2.使用须知**

本软件基于Matlab平台开发，使用时请在windows7及以上操作系统运行，建议采用Matlab2014b及以上版本。

如无Matlab软禁，请安装对应的环境文件(MCR文件)即可实现脱离平台运行。

## **3.操作说明**

### **3.1**

打开Matlab平台，单击打开按钮，选取untitled21_export文件，单击该文件打开。

![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/01d83840-bbc0-4790-bcd2-a3c8bdcee248)

 

### **3.2**

点击运行按钮。

![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/6531963b-ee16-4a15-b19e-457ad1c008ad)


 

### **3.3**

若程序出现以下提示，选择更改文件夹即可。若没有出现以下提示请看2.4。

![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/298b5d78-c0d5-47c4-88f6-fce5f5456351)


 

### **3.4**

打开后出现此运行界面，其中输入面板需要用户输入数据，输出面板为计算结果。
![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/2e94b435-1b08-4362-8355-697cd7066d80)



### **3.5**

动能修正系数可近似的取1，依据实际工程情况可以自行更改。

![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/c632ff16-ab7c-4545-bc44-55f2e53e8e4e)


### **3.6**

流量为各工况下的下泄流量，后续计算中如果仅有流量发生变更无须更改其余项，在流量处重新输入新的流量即可。

![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/0001ec70-99a9-4093-9b9c-b4ad1a767a54)


### **3.7**

重力加速度取9.8，修正系数取1.2特殊情况下可自行更改。
![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/160dd40e-027e-4adc-8b5f-970a3b078b44)



### **3.8**

急缓流选定中根据实际工程进行选择，后续程序会自动选择对应的工况求解。

![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/de9a520b-73b8-42e2-808a-1aee85389f90)


### **3.9**

渠上水头（一般为各工况水位-渠道起始端底高程）
![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/fabae5ff-8de1-4c1d-9638-c1fe8f1e5602)



### **3.10**

根据测量图输入断面参数。输入时请采用英文输入法。右侧断面参数在输入时如有连续的数字输入，在输入时请用逗号隔开(必须英文输入法)。
![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/ed8a0368-26b7-4b31-84dc-737040150332)



### **3.11**

在输入面板处输入完所有参数后，在输出面板点击运行按钮即可输出溢洪道水面线和临界水深。下图为使用实例。

![image](https://github.com/FISHCAT6/Calculation-of-water-surface-profile/assets/89964854/0064bad5-1f22-4563-9091-73ea93058cbf)

 


