FROM syping/qt5-static-llvm-mingw:5.12.8

WORKDIR /

RUN apt-get update && \
    apt-get install -y curl git lua5.2 openssl upx wget && \
    rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
