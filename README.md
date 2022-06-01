# besttrace4

北京移动25858
http://speedtest.bmcc.com.cn:8080/speedtest/upload.php

北京联通43752
https://beijing.unicomtest.com:8080/speedtest/upload.php

天津电信35722
http://tjrate.tjtele.com:8080/speedtest/upload.php

上海电信3633
http://speedtest1.online.sh.cn:8080/speedtest/upload.php

```
wget https://cdn.ipip.net/17mon/besttrace4linux.zip && sudo unzip besttrace4linux.zip -d /opt/besttrace && sudo chmod +x /opt/besttrace/besttrace

#北京移动
sudo /opt/besttrace/besttrace -g cn speedtest.bmcc.com.cn

#北京联通
sudo /opt/besttrace/besttrace -g cn beijing.unicomtest.com

#天津电信
sudo /opt/besttrace/besttrace -g cn tjrate.tjtele.com
```
