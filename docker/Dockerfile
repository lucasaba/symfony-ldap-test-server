FROM osixia/openldap
LABEL maintainer="wshihadeh.devx@gmail.com"
ENV LDAP_ORGANISATION="Al-waleed Test Org"
ENV LDAP_DOMAIN="symfony.com"
RUN mkdir /ldif-data
COPY ./data/fixtures.ldif /ldif-data/50-fixtures.ldif
