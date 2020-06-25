FROM syping/qt5-shared-llvm-mingw:5.12.9

WORKDIR /

RUN apt-get update && \
    apt-get install -y curl git lua5.2 nsis openssl wget && \
    rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
