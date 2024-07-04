# 002-certificate.md

### Create the Secret for the SSL Cert

```
kubectl create -n sni-ingress-gw secret tls ssltest-benmaynard-co-uk  \
  --key=../certificates/privkey.pem \
  --cert=../certificates/fullchain.pem
```
