FROM registry.access.redhat.com/ubi7/ubi:7.7

COPY *.sh /work/

RUN echo "Hi" && \
  chmod +x /work/*.sh

CMD "/work/entrypoint.sh"