# 12/05/26

- Tipos de Hashs

   - -m 0 -> MD5 = 32 hex (128 bits, sem salt)  
   - -m 100 -> SHA1 = 40 hex (160 bits)  
   - -m 1400 -> SHA256 = 64 hex (256 bits)  
   - -m 1700 -> SHA512 = 128 hex (512 bits)  
   - -m 900 -> MD4 = 32 hex  
   - -m 1300 -> SHA224 = 56 hex  

   - -m 1000 -> NTLM = 32 hex (Windows)  
   - -m 3000 -> LM = 32 hex maiúsculo (antigo Windows)  

   - -m 3200 -> bcrypt = 60 chars ($2a/$2b/$2y + salt)  
   - -m 1800 -> sha512crypt = ~106 chars ($6$)  
   - -m 500 -> md5crypt = ~34 chars ($1$)  
   - -m 1500 -> descrypt = 13 chars fixos  
   - -m 7400 -> sha256crypt = ~63–90 chars ($5$)  

   - -m 1410 -> SHA256 + salt = 64 hex + salt externo  
   - -m 1710 -> SHA512 + salt = 128 hex + salt externo  

   - -m 8900 -> scrypt = variável ($s0$)  

   - -m 10000 -> Django PBKDF2-SHA256 = 100+ chars  
   - -m 10900 -> PBKDF2-HMAC-SHA256 = variável  
   - -m 12100 -> PBKDF2-HMAC-SHA512 = variável  

   - -m 5500 -> NetNTLMv1 = variável (auth rede)  
   - -m 5600 -> NetNTLMv2 = variável (mais forte)  

   - -m 17300 -> SHA3-224 = 56 chars  
   - -m 17400 -> SHA3-256 = 64 chars  
   - -m 17600 -> SHA3-512 = 128 chars  

   - -m 11 -> Joomla MD5 = 32 hex  
   - -m 400 -> phpass = ~34 chars ($P$ / $H$)  
   - -m 2611 -> vBulletin = 32 hex  
   - -m 2711 -> vBulletin >= 3.8.5 = 32 hex  
   - -m 7900 -> Drupal7 = 55–100 chars  
   - -m 21 -> osCommerce = 32 hex  

   - -m 13600 -> ZIP = variável  
   - -m 17200 -> PKZIP = variável  
   - -m 12500 -> RAR3 = ~20–40 chars  
   - -m 13000 -> RAR5 = ~80+ chars  
   - -m 11600 -> 7-Zip = variável  

   - -m 9600 -> Office 2013 = variável  
   - -m 9700 -> Office 2010 = variável  
   - -m 9800 -> Office 2013 = variável  

   - -m 10400 -> PDF 1.1–1.3 = 32 hex  
   - -m 10500 -> PDF 1.4–1.6 = 32 hex  
   - -m 10600 -> PDF 1.7 = 32 hex ou AES derivado  

   - -m 15700 -> Ethereum Wallet = 32–66 hex  
   - -m 11300 -> Bitcoin/Litecoin wallet.dat = binário criptografado  




