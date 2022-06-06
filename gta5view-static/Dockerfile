FROM syping/qt5-static-llvm-mingw:5.15.4

WORKDIR /

RUN apt-get update && \
    apt-get install -y cmake curl git lua5.2 openssl upx wget && \
    rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
