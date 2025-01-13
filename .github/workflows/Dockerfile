FROM ubuntu:18.04 # 使用 Ubuntu 18.04 或其他包含 Python 2 的镜像

RUN apt-get update && apt-get install -y \
    curl git ftp lftp wget libarchive-tools ccache \
    python2 python2-dev python3 \ # 这里安装 python2
    pngcrush schedtool dpkg-dev liblz4-tool make optipng maven device-tree-compiler \
    libc6-dev-i386 lib32ncurses5-dev libx11-dev lib32z-dev libgl1-mesa-dev xsltproc \
    libxml2-utils libbz2-dev libbz2-1.0 libghc-bzlib-dev squashfs-tools lzop flex tree \
    build-essential bc gcc-aarch64-linux-gnu gcc-arm-linux-gnueabi libssl-dev libfl-dev \
    pwgen libswitch-perl policycoreutils minicom libxml-sax-base-perl libxml-simple-perl \
    zip unzip tar gzip bzip2 rar unrar llvm g++-multilib bison gperf zlib1g-dev automake

WORKDIR /app
COPY . /app

CMD ["/bin/bash"] # 或者你的默认命令
