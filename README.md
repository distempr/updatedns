# updatedns

Zone ID can be obtained using the following URL

```
https://api.cloudflare.com/client/v4/zones?name=example.com
```

Record ID with the following URL

```
https://api.cloudflare.com/client/v4/zones/:zone_identifier/dns_records?name=record.example.com&type=A
```

Replace `:zone_identifier` with the zone ID.

For authentication with CloudFlare, use "Authorization: Bearer :token" to the requests.
