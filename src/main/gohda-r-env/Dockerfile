FROM hub.arachnenetwork.com/r-env:1.0.4
MAINTAINER jiemx2008@163.com
VOLUME /tmp
VOLUME /libs-r
VOLUME /dist
RUN apt-get --allow-releaseinfo-change update && apt-get install -y sudo
RUN rm -f /usr/bin/java && update-alternatives --config java
ENV R_INSTALL_SCRIPT=libs.r