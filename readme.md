# Teamspeak 3 | 2 servers docker config setup
> Docker based TS 3 server setup with 2 servers running on one host on different ports with NGINX reverse proxy with load balancing

## Overview 
**THIS PROJECT IS NOT PRODUCTION READY**

This project is experimental setup for solving issue of setting two TS3 servers with NGINX reverse procy and load balancing. 

## Setup
1. Setup first server and database with `docker-compose up`
2. Connect and setup admin token.
3. Stop `docker` using CTRL+C.
4. Uncomment second TS server in `docker-compose.yml` and in NGINX config.
5. Do the same with second TS server.
