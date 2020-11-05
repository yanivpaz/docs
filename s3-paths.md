# docs

When I took the exam, I was presented with both styles of accessing an S3 bucket.
Per: http://docs.aws.amazon.com/AmazonS3/latest/dev/UsingBucket.html#access-bucket-intro

Amazon S3 supports both virtual-hosted–style and path-style URLs to access a bucket.

In a virtual-hosted–style URL, the bucket name is part of the domain name in the URL. For example:

http://bucket.s3.amazonaws.com

http://bucket.s3-aws-region.amazonaws.com.

In a virtual-hosted–style URL, you can use either of these endpoints. If you make a request to the http://bucket.s3.amazonaws.com endpoint, the DNS has sufficient information to route your request directly to the region where your bucket resides.

For more information, see Virtual Hosting of Buckets.

In a path-style URL, the bucket name is not part of the domain (unless you use a region-specific endpoint). For example:

US East (N. Virginia) region endpoint, http://s3.amazonaws.com/bucket

Region-specific endpoint, http://s3-aws-region.amazonaws.com/bucket

