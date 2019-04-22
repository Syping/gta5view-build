FROM syping/qt5-shared-mingw-openssl:5.12.3

RUN apt-get update && \
    apt-get install -y git lua5.2 nsis openssl && \
    rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
