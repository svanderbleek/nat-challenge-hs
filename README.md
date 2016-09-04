## Firewall

1. sourceHost -> IP packet -> destinationHost
- sH IP:port -> externalHost IP:port
- port range 1025-5535
- no conflict assignment
- repeated sH -> eH use same map
- sent to eH w/ firewall public IP
- eH -> interalHost Firewall public IP:port
- destinationHost IP port in 2 and 4
- to pick sH
- ignore traffic from sH to public
