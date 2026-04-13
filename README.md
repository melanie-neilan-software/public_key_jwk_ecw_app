Pentest application using github cached layers. Sandbox.


code used to generate keypair: 

`openssl genrsa -out private_key.pem 2048
openssl rsa -in private_key.pem -pubout -out public_key.pem`


`openssl req -new -x509 -key private_key.pem -out certificate.pem -days 1095 -subj "/CN=melanie-neilan-software.github.io"`
