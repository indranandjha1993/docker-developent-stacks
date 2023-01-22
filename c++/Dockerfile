FROM gcc:latest

COPY src/ /c++

WORKDIR /c++

RUN g++ -o main main.cpp

CMD ["./main"]
