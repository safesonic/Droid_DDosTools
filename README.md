Droid_DDosTools
----------------

> ZhuZhiHao  > 2016-2-25  
> 2016-4-17  

- **不要用于非法行为！！**

### 啥
- 几个简单的DDOS小程序。
- [BoNeSi大规模网际流量模拟](./README.BoNesi.md)

### 编译
- `arm-linux-androideabi-gcc *.c -lpthread`

### 安装
- 预编译可执行文件在`Droid_DDosTools/Bins`下，请将Bins文件夹及其文件移动到 Android `/data/data/` 下
- `adb push Droid_DDosTools/Bins /data/data/Bins && chmod 755 /data/data/Bins -R`
- `export PATH=$PATH:/data/data/Bins`
- 试试看吧！
- `which Chargen && Chargen`

### TODO
- 以后会有UI界面的，等一等吧...
- 移植BoNeSi僵尸网络模拟/大规模网际流量模拟

### 关于我
- [ZhuZhiHao|Linuxer+高中生](http://zhu-zhi-hao.github.io/)
- NOTE：**我是单身狗**


