FROM osixia/openldap
LABEL maintainer="wshihadeh.devx@gmail.com"
ENV LDAP_ORGANISATION="Al-waleed Test Org"
ENV LDAP_DOMAIN="symfony.com"
COPY ./slapd.conf /etc/ldap/slapd.d/slapd.conf
COPY ./data/base.ldif /container/service/slapd/assets/config/bootstrap/ldif/50-base.ldif
COPY ./data/fixtures.ldif /container/service/slapd/assets/config/bootstrap/ldif/50-fixtures.ldif

