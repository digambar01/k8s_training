###################




```
curl -H "Host: my.kubernetes.example" http://172.17.0.55:32103/webapp1
--o/p
<h1>This request was processed by host: webapp1-6d7df9f8d-qqsl2</h1>

---

curl -H "Host: my.kubernetes.example" http://172.17.0.55:32103/webapp2
--o/p
<h1>This request was processed by host: webapp2-6d48b8ff76-4q62h</h1>

---

curl -H "Host: my.kubernetes.example" http://172.17.0.55:32103/webapp3
--o/p
<h1>This request was processed by host: webapp3-7df59dc67b-wpcsp</h1>

```
