Bootstrap: docker
From: centos:6

%post

# Deps
yum groupinstall -y 'Development Tools'

yum install -y wget glibc-devel.i686 libgcc.i686 libstdc++.i686 texinfo pcre-devel openssl-devel curl-devel mesa-libGL-devel

yum install -y libibverbs-devel

yum install -y zlib-devel

yum clean all -y

%environment

# for Pymca
SPECFILE_USE_GNU_SOURCE=1
export SPECFILE_USE_GNU_SOURCE
