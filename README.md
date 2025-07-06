# Hosti ✍🏻
<img src="https://raw.githubusercontent.com/killukeren/Hosti/refs/heads/main/image.png"/>
Adalah automation tools untuk mendeteksi celah misconfig Host Header injection pada beberapa domain/subdomain pada website.

# Host Header Injection ✍🏻
<img src="https://raw.githubusercontent.com/killukeren/Hosti/refs/heads/main/hostin.png"/>
Host Header Injection adalah jenis kerentanan keamanan di mana penyerang bisa memanipulasi header Host atau X-Forwarded-Host dalam permintaan HTTP untuk menyebabkan efek tak diinginkan pada sisi server, seperti  open redirect, cache poisoning, dan bypass autentikasi.

# Install Tools ✍🏻
```
$ sudo apt install python3 python3-pip
$ git clone https://github.com/killukeren/Hosti.git
$ cd Hosti
$ pip3 install -r requirement-tools.txt
$ python3 hosti.py
```
# Referensi 
https://www.acunetix.com/vulnerabilities/web/host-header-attack&/
https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/17-Testing_for_Host_Header_Injection
