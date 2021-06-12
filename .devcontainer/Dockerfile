FROM gcc:11.1.0

RUN echo 'deb http://deb.debian.org/debian testing main' > /etc/apt/sources.list.d/testing.list & \
    apt update && apt install -qq -y -t testing build-essential cmake