# Uninstall Aliyun-services  

## 卸载阿里云盾（安骑士）
```  
wget http://update.aegis.aliyun.com/download/uninstall.sh  
chmod +x uninstall.sh  
./uninstall.sh  
wget http://update.aegis.aliyun.com/download/quartz_uninstall.sh  
chmod +x quartz_uninstall.sh  
./quartz_uninstall.sh  
```  
## 删除残留
```  
pkill aliyun-service  
rm -fr /etc/init.d/agentwatch /usr/sbin/aliyun-service  
rm -rf /usr/local/aegis*  
```  

Reference: https://www.wn789.com/11468.html  
