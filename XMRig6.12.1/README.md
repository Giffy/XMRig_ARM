# Compiled MoneroOcean XMRig miner for ARM 32 & 64bits platform

Oficial XMRig fork released 02 Dec 2021

Source code : https://github.com/xmrig/xmrig/releases/tag/v6.16.1


<b>Usage:</b>

./xmrig-notls -o <POOL.URL:PORT> -u <YOUR:XMR:WALLET> -k --rig-id <RIG-NAME>
  
<b>Example:</b>

sudo ./xmrig-notls -o fr.moneroocean.stream:10001 -u 4XX6uXXf6XX7mXXJ2XXMFXX5eXXTVXXLm7XX....XXUJXXuL -k --rig-id device1 
  
<br>
  
### Download it directly to the device using:
  
curl https://raw.githubusercontent.com/Giffy/XMRig_ARM/main/XMRig6.12.1/xmrig-notls.tar.gz -o xmrig.tar.gz

tar xvf xmrig.tar.gz  

chmod 700 xmrig-notls

sudo ./xmrig-notls -o fr.moneroocean.stream:10001 -u <YOUR_WALLET>  -k --rig-id device1 
