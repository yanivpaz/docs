# S3 encryption
SSE - server side

## AWS keys  
* SSE-S3 (AES-256) - AWS manged keys  
* SSE-KMS (AWS-KMS)  -My KMS key 

## not AWS keys 
* SSE-C - Customer provide the keys outside AWS - 
  - User manage the keys 
  - but AWS encrypt/decrypet 
  - Key not saved in AWS ( provided in the requesdt header for encryption/decryption  )

* Client side - User encrypt data before upload , and decrypt ind download  .

