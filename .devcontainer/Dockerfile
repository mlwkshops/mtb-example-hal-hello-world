ARG VARIANT="stable"
FROM mlworkshop101/modus-linux-30:${VARIANT}

RUN mkdir /home/builder/mtb-workspace
RUN mkdir /home/builder/mtb-workspace/mtb-example-hal-hello-world
WORKDIR /home/builder/mtb-workspace/mtb-example-hal-hello-world

COPY --chown=builder:builder . .

ARG TARGET="CY8CPROTO-062-4343W"
RUN /opt/ModusToolbox/tools_3.0/library-manager/library-manager-cli -p . --add-bsp-name ${TARGET}