# Deploy Node.js application with Caddy, Docker & docker-compose on DigitalOcean

![](./ff212916-a5c4-43b3-83c4-0d9617bfef6e.png)


1.0 Configure Docker & Caddy Server

    1.1 Create Dockerfile
    1.2 Create docker-compose.yml file
    1.3 Create Caddyfile
    1.4 Create deploy script

2.0 Create Digital Ocean Droplet

3.0 Point domain at droplet

4.0 Deploy application

    4.1 SSH in to server
    4.2 Git pull repo `git pull `
    4.3 Run deployment script

5. Test SSL certificate
`https://www.ssllabs.com/ssltest/`

Notes:
On Mac OS you need to mode the deployment script to execute it
`chmod +x deploy.sh`