## Open Media Vault 6
- edit /etc/systemd/resolved.conf and enter `Cache=no` `DNSStubListener=no`


<img width="833" alt="systemd-resolved" src="https://user-images.githubusercontent.com/78471292/220921274-e118df7d-2c48-4910-80f8-d13910f8f8dd.png">

- restart systemd-resolved: systemctl restart systemd-resolved

