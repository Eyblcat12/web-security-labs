


#hehehehehe

![Login page](./image/image1.png)

---

#CSRF
---
#What is the impact of a CSRF attack?
---
#How does CSRF work?
POST /email/change HTTP/1.1
Host: vulnerable-website.com
Content-Type: application/x-www-form-urlencoded
Content-Length: 30
Cookie: session=yvthwsztyeQkAPzeQ5gHgTvlyxHfsAfE

email=wiener@normal-user.com

With these conditions in place, the attacker can construct a web page containing the following HTML:

![image3](./image/image3.png)

---
while web of attacker can be
![image4](./image/image4.png)
---

#LAB



