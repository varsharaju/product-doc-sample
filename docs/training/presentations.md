## Presentations

</br>
[Jenkins World 2016 Talk](https://www.youtube.com/watch?v=vOL0patATNI)
</br></br>

## Training Video
</br></br>
Check out this cool video [AWS CLI Configuration](https://www.youtube.com/watch?v=g0WJsKrXtoQ&feature=youtu.be)

</br></br>

## Tutorials

#### Exercise 1 : Setup AWS cli

!!! info
    This lab involves setting up the AWS cli on your laptop to work with your resources in AWS


* Install aws cli for your machine using instructions provided [here](https://docs.aws.amazon.com/cli/latest/userguide/install-macos.html)
* Configure your profiles for each AWS account that you will be accessing

        aws configure --profile test1
        AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
        AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
        Default region name [None]: us-west-2
        Default output format [None]: json

* This should create the [test1] profile with the required credentials, region, and output information in ~/.aws/credentials and ~/.aws/config files
* You should now be able to use aws cli to work with resources in that account that you have been provided access to

        For example:
        aws s3 cp s3://mybucket/mykey .
