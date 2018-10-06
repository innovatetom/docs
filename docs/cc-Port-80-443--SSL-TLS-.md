---
title: "Port 80/443 (HTTPS)"

---
By default SHOUTcast and Icecast servers run on non-standard ports resulting in the :8000 (or other number) on the end. In some places these are blocked by a firewall. That is why we offer a free port 80 proxy.

To use it replace the hostname:port by *username*.radioca.st. So for example http://meyskens.radioca.st/.
If you need HTTPS, you can also use https:// (eg. https://meyskens.radioca.st/).

Should this not work 24 hours after activating your account please contact our support team.

> Please note we do not offer this service for reseller sub-accounts due to username conflict.

> Icecast 2.4 will report incorrect listener IPs in it's own APIs. This will soon be fixed in version 2.5. You can follow the process on [the Icecast issue tracker](https://gitlab.xiph.org/xiph/icecast-server/issues/1959). Centova Cast will be able to display the IP correct.
