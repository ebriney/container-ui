FROM centos
RUN yum install -y yum-utils && \
yum-config-manager \
    --add-repo \
    https://docs.docker.com/engine/installation/linux/repo_files/centos/docker.repo && \
    yum makecache fast && \
    yum -y install docker-engine
    