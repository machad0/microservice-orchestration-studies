# Kong 
Run: `docker-compose build && docker-compose up -d` inside `compose/`

If you wish to scale kong instances, run: `docker-compose scale kong=3`

This Kong instance contains:
- Nginx
- Consul
- Postrgres
- Kong-dashboard
- Load Balacing services
