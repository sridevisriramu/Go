#creating from scratch

FROM golang:latest
COPY main1.go myDocker/
WORKDIR myDocker/
EXPOSE 12345
RUN ["go",  "get", "github.com/gorilla/mux"]
CMD ["go", "run", "main1.go"]