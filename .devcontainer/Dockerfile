ARG VARIANT="stable"
FROM mlworkshop101/modus-linux-30:${VARIANT}

USER root

RUN mkdir /mtb-workspace
RUN mkdir /mtb-workspace/mtb-example-hal-hello-world
WORKDIR /mtb-workspace/mtb-example-hal-hello-world

COPY . .