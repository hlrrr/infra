# Routing Policy
  - **Simple routing policy** \
    Use for a single resource that performs a given function for your domain, for example, a web server that serves content for the example.com website. You can use simple routing to create records in a private hosted zone.
  
  - **Failover routing policy**\
    Use when you want to configure active-passive failover. You can use failover routing to create records in a private hosted zone.
  
  - **Geolocation routing policy**\
    Use when you want to route traffic based on the location of your users. You can use geolocation routing to create records in a private hosted zone.
  
  - **Geoproximity routing policy**\
    Use when you want to route traffic based on the location of your resources and, optionally, shift traffic from resources in one location to resources in another location. You can use geoproximity routing to create records in a private hosted zone.
  
  - **Latency routing policy**\
    Use when you have resources in multiple AWS Regions and you want to route traffic to the Region that provides the best latency. You can use latency routing to create records in a private hosted zone.
  
  - **IP-based routing policy**\
    Use when you want to route traffic based on the location of your users, and have the IP addresses that the traffic originates from.
  
  - **Multivalue answer routing policy**\
    Use when you want Route 53 to respond to DNS queries with up to eight healthy records selected at random. You can use multivalue answer routing to create records in a private hosted zone.
  
  - **Weighted routing policy**\
    Use to route traffic to multiple resources in proportions that you specify. You can use weighted routing to create records in a private hosted zone.
