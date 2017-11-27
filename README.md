先在cpp中设定海康摄像头ip、端口、登入名和密码：
192.168.2.254
8000
admin
admin1234"



生成可执行文件必须放在lib文件夹下
或
.bashrc添加


export LD_LIBRARY_PATH=/home/keetsky/Desktop/HikMeaDis/lib${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}

export LD_LIBRARY_PATH=/home/keetsky/Desktop/HikMeaDis/lib/HCNetSDKCom${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}


编译：
$cd HikMeaDis

$mkdir build && cd build

$cmake ..

$make

