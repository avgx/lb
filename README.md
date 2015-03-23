# Nginx Load Balancer w/ Service Discovery

Example of dockerized load balancer using nginx + consul + consul-template (for service discovery and automatic nginx configuration file generation)

Routes to proxy:

    /user_service -> user service backend
    /catalog_service -> catalog service backend
    /cart_service -> cart service backend
    /my_business_service -> my business service backend
    /oms_service -> oms service backend

