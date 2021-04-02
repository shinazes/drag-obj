# Drag objects

## For launching
- generate a certificate: `openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem`
- launch https-server: `npx http-server -S -C cert.pem -o`