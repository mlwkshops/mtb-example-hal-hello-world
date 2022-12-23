ARG VARIANT="stable"
FROM pss-sw-gov-registry.vih.infineon.com/pssbuild/modus-linux-30:${VARIANT}

USER root

RUN mkdir /mtb-workspace
RUN mkdir /mtb-workspace/mtb-example-hal-hello-world
WORKDIR /mtb-workspace/mtb-example-hal-hello-world

COPY . .