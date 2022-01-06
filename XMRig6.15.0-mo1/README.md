# Compiled MoneroOcean XMRig miner for ARM 64bits platform

MoneroOcean's XMRig fork released 31 Aug 2021

Source code : https://github.com/MoneroOcean/xmrig/releases/tag/v6.15.0-mo1


<b>Usage:</b>

./xmrig-notls -o <POOL.URL:PORT> -u <YOUR:XMR:WALLET> -k --rig-id <RIG-NAME>
  
<b>Example:</b>

./xmrig-notls -o fr.moneroocean.stream:10001 -u 4XX6uXXf6XX7mXXJ2XXMFXX5eXXTVXXLm7XX....XXUJXXuL -k --rig-id device1 
  
<br>
  
### Download it directly to the device using:
  
curl https://raw.githubusercontent.com/Giffy/XMRig_ARM/main/XMRig6.15.0-mo1/xmrig-notls.tar.gz -o xmrig.tar.gz
tar -xzvf xmrig.tar.gz
chmod 700 xmrig-notls
