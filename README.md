# Final Project – Basic Development and Operation

## Student Information

- **Name:** [ChenZhongLiang]  
- **Student ID:** [20242200]  
- **Email:** [m19979737518@163.com,2671943275@qq.com]  
- **Photo:**  
  ![My Photo](./myweb/html/Clark.jpg)

## Deployed Applications

- **Personal Website:** [http://100.58.169.156:8080](http://你的服务器IP:8080)  
- **Todo Application:** [http://100.58.169.156:8081](http://你的服务器IP:8081)
- ***But the server IP would be changed***

## Work Distribution (working alone)

- 100% Clark (completed individually)

## Repository Structure

- `.github/workflows/main.yml` – CI/CD pipeline
- `myweb/` – personal website source and Dockerfile
- `docker-compose.yml` – service orchestration
- `README.md` – this file

## How to Deploy (for reference)

1. Clone the repository.
2. Run `docker compose up -d --build` on a server with Docker & Compose installed.
3. Access the two services on ports 8080 and 8081.