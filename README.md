# minio
Deploy minio as a docker compose

In `/opt/services/certs` put below files

```
domain_name.crt
domain_name.key
domain_name.fullchain.crt
```
In addition create 2 more files as below

```
public.crt   Put contents of domain_name.crt in this
private.key  Put contents of domain_name.key in this
```
Put all CAs, any intermediate CAs in `/opt/services/certs` as well as `/opt/services/certs/CAs`
