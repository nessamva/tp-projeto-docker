# Use a imagem oficial do nginx
FROM nginx:alpine

# Remover conteúdo padrão (opcional)
RUN rm -rf /usr/share/nginx/html/*

# Copiar os arquivos do site para o diretório padrão do nginx
COPY index.html /usr/share/nginx/html/index.html

# Expor porta (documentação — binding será configurado no docker compose)
EXPOSE 80

# Comando padrão do nginx já é CMD ["nginx", "-g", "daemon off;"] na imagem base
