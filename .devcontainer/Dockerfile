FROM mcr.microsoft.com/cbl-mariner/base/core:2.0
ARG PKGS="dotnet-sdk-7.0 azure-cli lynx git"
RUN tdnf update -y && \ 
    tdnf upgrade -y && \
    tdnf install -y ${PKGS} && \
    tdnf clean all
