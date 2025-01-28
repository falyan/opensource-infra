For configure .env file you should change ENCRYPTION_KEY & AUTH_SECRET, can be generated from this command :
"openssl rand -hex 16" -> for ENCRYPTION_KEY
"openssl rand -base64 32" -> for AUTH_SECRET