FROM ubuntu:latest
RUN apt-get update -y 
RUN apt-get install -y
RUN apt-get install clang -y
COPY . /usr/src/hostpital_system
WORKDIR /usr/src/hostpital_system
RUN clang++ -o Programm hospital_system.cpp
CMD ["./Programm"]

