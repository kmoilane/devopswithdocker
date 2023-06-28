# Start from the ubuntu image version 20.04
FROM		  ubuntu:20.04

#Use /usr/src/app as our workdir
WORKDIR		/usr/src/app

RUN		    apt-get update && \
		      apt-get install -y curl

COPY      curl-script.sh .

CMD 		  ./curl-script.sh
