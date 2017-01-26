# Nginx S3 Proxy

If you need to lock down your s3 bucket and would like an easy way to proxy your s3 endpoint from a secure server.


 
##### Example  
``` docker run -it -p 8888:80 -e 'S3_BUCKET_URL_=<Bucket Url>' --name nginx nginx-s3-proxy ```
