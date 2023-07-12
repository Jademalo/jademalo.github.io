FROM mcr.microsoft.com/devcontainers/base:bullseye

# Install nginx
RUN apt-get update && apt-get install -y nginx

# Host source with nginx
RUN rm -rf /var/www/html
RUN ln -s /workspaces/jademalo.github.io /var/www/html