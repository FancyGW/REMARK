20180331
win10+ubuntu16.04
1. 打开终端
2. sudo fdisk -l  
3. 查看是哪个disk出了问题记下来
4. sudo ntfsfix /dev/sda5    //sda是几就写几
