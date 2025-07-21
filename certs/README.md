
## 🛠️ Perintah CMD
# Cara Generate `cert.pem` dan `key.pem`

## 📁 Lokasi File Config
Pastikan file config `openssl.cnf` ada di: 

```sh
set OPENSSL_CONF=C:\openssl\apps\openssl.cnf

openssl req -x509 -newkey rsa:2048 -nodes -keyout key.pem -out cert.pem -days 365
