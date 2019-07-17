Bootstrap: docker
From: centos:6

%post

# Deps
yum groupinstall -y 'Development Tools'

yum install -y wget glibc-devel.i686 libgcc.i686 libstdc++.i686 texinfo pcre-devel openssl-devel curl-devel

yum install -y libibverbs-devel

yum install -y zlib-devel

yum clean all -y

