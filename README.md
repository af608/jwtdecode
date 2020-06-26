
# jwtdecode

Simple cli tool (for macOS) to decode JWT

# Requires

The command-line JSON processor "jq"

=> `brew install jq`

# Install

=> `wget https://raw.githubusercontent.com/af608/jwtdecode/master/jwtdecode`

=> `chmod u+x ./jwtdecode`

# Use

```sh
jwtdecode eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c

{
  "alg": "HS256",
  "typ": "JWT"
}
{
  "sub": "1234567890",
  "name": "John Doe",
  "iat": 1516239022
}
```
