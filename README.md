# MusicYou
Unofficial NetEase Cloud Music player


需要的target为33（bt sdk） 修改login为uwp


# 需要（可以custom）修改的地方

app/src/main/java/com/kyant/ncmapi/下的两个文件

Apiaction 和login 

### api
修改request（在这个仓库已经修改好 可以直接构建使用）


os=ios 使用ios api登录 但是登录不了会提示忙碌 需要修改成下面任意一个

UWP版


os=uwp;appver=1.4.1;osver=10.0.19041.1;deviceId=11111111111111111111111111111111


Windows 版(未测试)


os=pc;appver=2.10.2.200154;osver=Microsoft-Windows-10--build-19041-64bit;deviceId=0000000000000000000000000000000000000000000000000000;mode=To%20be%20filled%20by%20O.E.M.;channel=netease
