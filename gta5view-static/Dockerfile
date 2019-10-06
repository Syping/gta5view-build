FROM syping/qt5-static-mingw-openssl:5.12.5

RUN apt-get update && \
    apt-get install -y curl git lua5.2 openssl && \
    rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
