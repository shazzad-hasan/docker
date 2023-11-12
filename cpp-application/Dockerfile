FROM gcc:latest 

COPY . /cpp-application

WORKDIR /cpp-application

RUN g++ -o main main.cpp

CMD [ "./main" ]