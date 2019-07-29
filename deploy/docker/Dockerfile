FROM BASEIMAGE

COPY metrics-server /

COPY passwd /etc/passwd

USER metrics-server

ENTRYPOINT ["/metrics-server"]
