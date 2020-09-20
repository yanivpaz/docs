# S3 encryption
## AWS keys  
* SSE-S3 - AWS manged keys  
* SSE-KMS -My KMS key 

## no AWS keys 
* SSE-C - Customer provide the key outside AWS - 
  User manage the keys 
  but AWS encrypt/decrypet 
  Key not saved in AWS ( provided in the header)

* Client side - encrypt before upload 
