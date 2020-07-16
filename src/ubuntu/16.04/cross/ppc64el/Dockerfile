FROM mcr.microsoft.com/dotnet-buildtools/prereqs:ubuntu-16.04-crossdeps

# Install binutils-aarch64-linux-gnu
RUN apt-get update \
    && apt-get install -y \
        binutils-powerpc64el-linux-gnu \
    && rm -rf /var/lib/apt/lists/*

ADD rootfs.ppc64el.tar crossrootfs
