FROM kong:latest

LABEL description="Alpine + Kong + kong-oidc plugin"

USER root
RUN apk update && apk add git unzip luarocks
RUN luarocks install kong-oidc

USER kong