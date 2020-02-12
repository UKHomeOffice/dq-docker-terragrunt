FROM hashicorp/terraform:0.11.14

RUN apk add --update --upgrade --no-cache bash git openssh
RUN apk upgrade libtasn1=1.8.5-r0
RUN apk upgrade musl=1.1.20-r5
RUN apk upgrade curl=7.64.0-r2
RUN apk upgrade libgcrypt=1.8.5-r0

ADD https://github.com/gruntwork-io/terragrunt/releases/download/v0.21.12/terragrunt_linux_amd64 /usr/local/bin/terragrunt

RUN chmod +x /usr/local/bin/terragrunt

WORKDIR /apps

ENTRYPOINT []
