# gitskills
import requests
r=request.get("http://www.baidu.com")
r.encoding=r.apparent_encoding
print(r.text)
