FROM  gcc:latest as build
COPY . /usr/src/cpp_test
WORKDIR /usr/src/cpp_test
RUN g++ -o test hospital_system.cpp

FROM ubuntu:latest
WORKDIR /usr/src/cpp_test
COPY --from=build /usr/src/cpp_test .
CMD ["./test"]