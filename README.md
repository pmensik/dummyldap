#Installation

```sh
mkdir dummyldap && cd $_
curl -Ls intelie.github.io/dummyldap | sh
```
LDAP server is afterwards running on port 1389. You should bind to a DN `uid=$username,ou=users,ou=system` where `$username` is either test1 or tests2 (passwords are the same).
