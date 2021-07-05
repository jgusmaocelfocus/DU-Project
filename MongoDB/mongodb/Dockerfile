# version image mongo
# sudo inactive
FROM mongo:4.2

RUN apt-get update && apt-get upgrade -y
RUN mkdir /home/mongodb
RUN chown mongodb:mongodb /home/mongodb
	
USER mongodb

