FROM alpine:3.12.0

RUN apk update && apk add --no-cache wget
RUN wget https://storage.googleapis.com/spinnaker-artifacts/spin/1.17.3/linux/amd64/spin
RUN chmod +x spin
RUN mv spin /usr/local/bin

CMD tail -f /dev/null