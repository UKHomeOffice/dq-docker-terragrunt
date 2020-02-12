FROM hashicorp/terraform:0.11.14

RUN apk add --update --upgrade --no-cache bash git openssh

ADD https://github.com/gruntwork-io/terragrunt/releases/download/v0.21.12/terragrunt_linux_amd64 /usr/local/bin/terragrunt

RUN chmod +x /usr/local/bin/terragrunt

WORKDIR /apps

ENTRYPOINT []
