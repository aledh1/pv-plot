Command to download files from S3:

DON'T DO THIS THOUGH!
aws s3 sync s3://pv-plot-configuration .


Command to push changes back into S3 bucket:

aws s3 cp --recursive . s3://pv-plot-configuration/


This assumes the pv-plot IAM user is configured on the machine.