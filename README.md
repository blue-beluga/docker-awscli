
# [<img src=".bluebeluga.png" height="100" width="200" style="border-radius: 50%;" alt="@fancyremarker" />](https://github.com/blue-beluga/docker-aws) bluebeluga/aws

Alpine Linux image with [Amazon Web Services Command Line Interface](http://aws.amazon.com/cli/).

## Usage

`docker run -it -v $HOME/.aws:/home/aws/.aws bluebeluga/awscli aws s3 ls`
