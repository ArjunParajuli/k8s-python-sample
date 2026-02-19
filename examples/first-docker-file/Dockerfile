FROM ubuntu:latest
WORKDIR /app
COPY . .
RUN apt update && apt install python3 -y
CMD ["python3", "app.py"]

