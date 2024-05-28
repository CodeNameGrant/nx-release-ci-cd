FROM nginx:1.17.8-alpine
LABEL org.opencontainers.image.source=https://github.com/CodeNameGrant/nx-release-ci-cd
COPY dist/apps/reporting /usr/share/nginx/html/reporting
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]