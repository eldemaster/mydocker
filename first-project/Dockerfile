FROM alpine:3.7

WORKDIR /mydir 
RUN apk update

RUN touch hello.txt 
COPY local.txt . 

CMD ["/bin/bash"]