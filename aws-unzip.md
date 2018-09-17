## Function to extract zip files uploaded to S3

Files are extracted in place in the same bucket as where the zip file was uploaded. Any files present with the same name are overwritten. The zip file is optionally deleted at the end of the operation.

References:

- [https://github.com/Craftware/aws-lambda-unzip]