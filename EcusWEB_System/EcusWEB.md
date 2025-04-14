10.134.7.79  2.0开发机 F3200568 / F3200568 

## 数据库

Oracle 数据库

WEBCUS 数据库：

- WZX_FILE  用户信息表

- WZC_FILE  法人关务代码的连接信息

  ![ECUSII.WZC_FILE表](D:\Notes\EcusWEB_System\images\ECUSII.WZC_FILE表.png)

-  WZO_FILE 法人表 

  |            公司            | 外销 wzo01 | 内销 wzo06 | 设备 wzo09 |
  | :------------------------: | :--------: | :--------: | :--------: |
  |  富泰華工業(深圳)有限公司  | ctbsfthsz  |  csfthnsz  | cshfjsbsz  |
  | 深圳富泰宏精密工業有限公司 | ctbsfihsz  |            |            |

- WZQ_FILE 法人关务代码表


 ECUSII 数据库：

- FIELDS_DICT 数据字典 

## 文件

delphi 语言

-  clas/uSaprfc.pas    Stype所在位置，查找数据库接口 ；
-  文件下面 .apsx 查找标签 如：dl_bsh30 是哪个输入框；
-  文件下面  .aps  查看代码；
-  文件下面  .design 查看表格样式，点击某个输入框或者标签查看其id、属性、方法；

## 参数

### 全局变量参数  viewstate['gXXX']

```pascal
viewstate['gUser']  :='X2008399';    //賬號
viewstate['gRight'] :='CLASS-A+';    //權限
viewState['gDbs']   :=MAIN_DB_NAME;  //
viewState['gBook']  :='E535723A008'; //賬冊
viewState['gCocode']:='4403948992';  //法人代碼
viewState['gConame']:='深圳富泰宏精密工業有限公司';  //法人名称
viewstate['gGroup'] :='Q2X000';      //部门
viewstate['gIp'] :='Q2X000';         //ip地址
viewstate['condition']:='';          //
viewstate['gErp']:='TIPTOP';         //ERP类型
viewstate['gZone']:='1';             //地區 如  gZone=1 代表深圳
viewstate['gEcssrc'] := 'ecsdb';     //法人表WZO10 ？？
viewstate['gEpzwl'] :='CTBS';        //法人表WZO05 ？？
viewState['gPlant'] :='ctbsfihsz';   //外銷數據庫
viewState['gPlantsrc'] :='CTBSHFJCZZQ2X000';      //外销数据库别名 WZC_FILE表
viewstate['gCtrade']:='cshfjnzz';    //内销数据库
viewstate['gCtradesrc']:='cshfjnzz'; //内销数据库别名
viewstate['gSb'] :='';               //设备数据库
viewstate['gSbsrc'] :='';            //设备库别名的別名informix
```



## StarTeam

## 页面

### 后台设置

#### IT系统设置

pr=sys/cssysi107.aspx&text=IT系統設置

可以在这里看地区 gZone 代表的地区，如 1代表华南深圳

### 公用资料

### 备案

### 通关

### 关检融合

### 报核

### 加工区物流

### 综保区物流

### 外发加工

### 设备监管

### 协管

### 废料

### 查询统计

### 关务其他

### SAP抛转

### 金关二期

### 关务一体化系统

### 深超出料加工

### 特殊监管区业务申報

### 货通车辆备案管制

### 智慧稽查

### 边角料(电子签核)

### 深超膜晶显免表報关

### 耗料单账册