# Example of how to create AMI on AWS with Packer

## You need to have packer installed.

on macos:
`brew install packer`

## variables

You need to have env variables set for your AWS keys
```
export AWS_ACCESS_KEY_ID=MYACCESSKEYID
export AWS_SECRET_ACCESS_KEY=MYSECRETACCESSKEY
```

## run

Execute below build command

```
packer build createami.json
```
