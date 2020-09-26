FROM syping/qt5-shared-llvm-mingw:5.15.1

WORKDIR /

COPY mingw32-qt-cmake /usr/local/bin/
COPY mingw64-qt-cmake /usr/local/bin/

RUN apt-get update && \
    apt-get install -y cmake curl git lua5.2 nsis openssl wget && \
    rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
