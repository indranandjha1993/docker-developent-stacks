FROM gcc:latest

COPY src/ /c

WORKDIR /c

RUN gcc -o main main.c

CMD ["./main"]
