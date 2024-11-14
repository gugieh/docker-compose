ARG ubu_ver=22.04
FROM ubuntu:${ubu_ver}
WORKDIR /app
ENV city=kraków
COPY skrypt.sh /app
CMD ["bash", "-c", "./skrypt.sh && sleep infinity"]