# Environment setup
1. `virtualenv .venv`
1. `. .venv/bin/activate`
1. `pip install -r requirements.txt`
1. Configure AWS CLI
   1. `aws configure` (http://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html)
   1. `aws s3 ls katas-async-weather`
   1. If you still get permission denied, Tyr probably needs to add you to the bucket policy

# Deployment target
1. s3 bucket: `katas-async-weather`
1. URL: http://katas-async-weather.s3-website-us-east-1.amazonaws.com/