FROM  gcc:latest 
COPY . /usr/src/cpp_test
WORKDIR /usr/src/cpp_test
RUN g++ -o test hospital_system.cpp
CMD ["./test"]