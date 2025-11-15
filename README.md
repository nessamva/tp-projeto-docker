# 📦 Projeto Docker: Site Estático com Nginx + Apache HTTPD

Este projeto demonstra como criar e orquestrar dois containers usando Docker Compose:

- Um container Nginx servindo um site estático personalizado
- Um container Apache HTTPD rodando em paralelo

---

## 🗂️ Estrutura do Projeto

```text
projeto-docker/
├── docker-compose.yml
├── nginx-site/
│   ├── Dockerfile
│   └── index.html
├── apache-site/
│   └── Dockerfile

```
---

## Acessar os serviços

- http://localhost:8080 → site estático com Nginx

- http://localhost:8081 → página padrão do Apache HTTPD


