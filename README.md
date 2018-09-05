# Example of how to create AMI on AWS with Packer

##You beed 1st to install packer**

`brew install packer`

##Fork this repo**

You need to make env variables for your AWS keys
```
export AWS_ACCESS_KEY_ID=MYACCESSKEYID
export AWS_SECRET_ACCESS_KEY=MYSECRETACCESSKEY
```

**Execute below build command**

`packer build createami.json`
