# Nginx Reverse Proxy with Docker

A Docker setup using Nginx as a reverse proxy to route traffic between two web servers (Apache and Jetty).

## How to Run

1. Clone the repository using either HTTPS or SSH:

   - For **HTTPS**:
     ```bash
     git clone https://github.com/MouslimMOUDEN/reverse_proxy-nginx.git
     ```

   - For **SSH**:
     ```bash
     git clone git@github.com:MouslimMOUDEN/reverse_proxy-nginx.git
     ```

2. Navigate to the project directory:
   ```bash
   cd reverse_proxy-nginx
   ```

3. Start the containers:
   ```bash
   docker-compose up -d
   ```

4. Access the web servers:
   - Apache: `http://localhost`
   - Jetty: `http://localhost/app2`
