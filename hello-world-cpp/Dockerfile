FROM gcc:latest 

COPY . /hello-world-cpp

WORKDIR /hello-world-cpp

RUN g++ -o hello hello.cpp

CMD [ "./hello" ]