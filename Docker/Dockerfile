FROM ubuntu
WORKDIR /app
RUN apt-get update && apt-get install default-jre -y
COPY . .
CMD ["java","HelloWorld"]
