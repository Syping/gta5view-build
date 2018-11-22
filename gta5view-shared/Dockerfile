FROM syping/qt5-shared-mingw:5.9.7-ubuntu

RUN apt-get update && \
    apt-get install -y curl git lua5.2 nsis openssl  && \
    rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
