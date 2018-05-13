FROM rustlang/rust:nightly
MAINTAINER <seanpquig@gmail.com>

WORKDIR /var/www/microservice/
COPY . .

RUN rustc --version
RUN cargo install

CMD ["microservice"]