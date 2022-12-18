# Simpleton Service Montior

## History

I have a small server at home that freezes every week or so. I wanted a simple container that would keep checking on the services hosted on the server and, if things go wrong, control a switch through home assistant to force the power off so I can restart the server. I don't have enough free computers on my network to warrant Kubernetes (it also looks overly complex...) and I thought it would be fun to try.