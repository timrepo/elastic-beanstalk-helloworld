# hello world app deployed to Elastic Beanstalk

## another sample app for go+gin
https://github.com/sudo-suhas/go-beanstalk-gin

## Configure docker to access private repository
run CLI ```docker login``` to save auth token in **~/.docker/config.json**. Copy its content to dockercfg file and upload this file to a s3 bucket.
Set this file's s3 info in **Dockerrun.aws.json** file.
Note: ~/.docker/config.json file on MacOS may be empty, because it uses keychains to manage secrets.