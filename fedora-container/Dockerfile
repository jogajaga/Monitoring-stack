FROM fedora:latest
RUN dnf -y update && \
	dnf -y install curl htop bash iproute net-tools && \
	dnf clean all
WORKDIR /root
CMD ["htop"]
