FROM nginx:1.25.4-alpine

# Atualiza os pacotes do sistema para versões corrigidas
RUN apk update && apk upgrade --no-cache

# Adiciona o conteúdo do app
ADD app.gz /usr/share/nginx/html/

# Comando padrão do nginx
CMD ["nginx", "-g", "daemon off;"]
