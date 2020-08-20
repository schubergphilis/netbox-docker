FROM netboxcommunity/netbox:v2.8.9

COPY entrypoint.sh ./
RUN apk update && \
    apk upgrade && \
    apk add curl && \
    curl -L https://github.com/telia-oss/aws-env/releases/download/v1.0.2/aws-env-linux-amd64 > /usr/local/bin/aws-env && \
    chmod +x /usr/local/bin/aws-env && \
    chmod +x ./entrypoint.sh

ENTRYPOINT ["./entrypoint.sh"]
