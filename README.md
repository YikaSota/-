# -2
适用于Auto.js屏幕自动点击脚本;
该脚本适用于当前1920x1080的屏幕Android设备;
请不要随意使用;



做着玩，没有适用性;

device.wakeUp();
sleep(1000);
swipe(500, 1900, 500, 200, 500);//向上滑动(以下为解锁步骤
sleep(1000);
click(530,1760);
sleep(200);
click(530,1510);
sleep(200);
click(530,1760);
sleep(200);
click(835,1510);
sleep(200);
click(835,1760);
launchApp("DingTalk");//启动钉钉
sleep(6000);//等待6秒
click(535,2030);//点击工作台
sleep(8000);//等待8秒
click(117,1111);//点击健康打卡
sleep(10000);//等待10秒
click(145,1510);//进入打卡界面
sleep(5000);//等待5秒
text("获取").click();//点击获取地址
sleep(3000);//等待3秒
text("提交").click();//点击提交
sleep(1000);
back();
sleep(1000);
back();
sleep(1000);
back();
sleep(1000);//等待1秒
back();//返回
exit();//退出
