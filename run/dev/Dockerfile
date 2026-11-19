ARG os=10.3.20261112.0
ARG image=devbase
FROM ghcr.io/rpmbsys/php82build:${os}-${image}

LABEL org.opencontainers.image.source=https://github.com/rpmbsys/rpmbuild-php-8.2

RUN curl -sSL https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
