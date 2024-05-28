FROM nginx:1.17.8-alpine
LABEL org.opencontainers.image.source=https://github.com/CodeNameGrant/nx-release-ci-cd
COPY dist/apps/inventory /usr/share/nginx/html/inventory
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]