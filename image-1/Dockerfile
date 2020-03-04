FROM centos

COPY *.sh /work/

RUN echo "Hi" && \
  chmod +x /work/*.sh

CMD "/work/entrypoint.sh"