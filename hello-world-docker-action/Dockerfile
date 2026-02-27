FROM alpine:3.22
WORKDIR /usr/src
COPY ./entrypoint.sh .
COPY ../../check-if-this-works.sh .
RUN chmod +x entrypoint.sh
RUN chmod +x check-if-this-works.sh
ENTRYPOINT ["/usr/src/entrypoint.sh", "/usr/src/check-if-this-works.sh"]
