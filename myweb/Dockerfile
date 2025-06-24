#Base image
FROM nginx:latest 
RUN apt update -y
COPY shark /usr/share/nginx/html/
EXPOSE 80

# run nginx in foregroup mode vs background mode 
ENTRYPOINT ["nginx", "-g", "daemon off;"]
