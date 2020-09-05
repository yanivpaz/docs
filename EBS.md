# EBS 
## ssd 
gp2 - up to 10000 iops ( 3 iops per 1Gb)
io1,ios2- provioned iops ( io2 has better durability)  

## non ssd ( can be boot volumes) 
st1 - throuput optimized 
sc1  -cold storage 


https://aws.amazon.com/ebs/features/  
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-optimized.html  
provision iops ratio is   1:50 ( size : iops )  
