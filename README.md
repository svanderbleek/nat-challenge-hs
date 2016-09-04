status: jumbled notes

## Firewall

1. sourceHost -> IP packet -> destinationHost
2. sourceHost IP:port -> externalHost IP:port
- port range 1025-5535
- no conflict assignment
3. repeated sH -> eH use same map
4. sent to eH w/ firewall public IP
5. eH --> interalHost Firewall public IP:port
6. destinationHost IP port in 2 and 4
7. to pick sH
8. ignore traffic from sH to public
