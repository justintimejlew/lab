FROM ubuntu:24.04
WORKDIR /app
COPY greet .
RUN chmod +x greet
ENV GREATING=Hello
ENV NAME=World
CMD ["./greet"]
