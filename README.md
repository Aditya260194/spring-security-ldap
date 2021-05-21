#spring-security-ldap

1. Add necessary jar for spring security.

LDAP server
2. For LDAP server, we will create a server using spring only. Add dependency in pom for ldap
3. Provide settings in application.properties file regarding server.
4. Create ldif file using https://spring.io/guides/gs/authenticating-ldap/ url.

Authentication
5. Add configuration in SecurityConfig for ldap authentication.