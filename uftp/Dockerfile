FROM debian:sid
RUN apt-get update && \
	apt-get install -y \
	wget
RUN wget https://master.dl.sourceforge.net/project/unicore/Clients/UFTP-Client/1.5.0/unicore-uftp_1.5.0-1_all.deb
RUN apt-get install -y \
	./unicore-uftp_1.5.0-1_all.deb

