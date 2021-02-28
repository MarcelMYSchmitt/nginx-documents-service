FROM nginxinc/nginx-unprivileged:1.17.5-alpine

COPY ./nginx.conf ./nginx.conf
COPY ./documents ./documents

CMD ["nginx", "-g", "daemon off;", "-c", "/nginx.conf"]