# Use a imagem oficial do Nginx
FROM nginx:alpine

# Copie os arquivos index.html e styles.css para o diretório padrão do Nginx
COPY index.html /usr/share/nginx/html/index.html
COPY styles.css /usr/share/nginx/html/styles.css

# Exponha a porta 80
EXPOSE 80