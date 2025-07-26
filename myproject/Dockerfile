# Используем официальный образ nginx
FROM nginx:alpine

# Копируем содержимое вашей папки site/ в стандартную папку nginx
COPY site/ /usr/share/nginx/html

# (Опционально) Копируем свой nginx.conf, если нужно
# COPY nginx.conf /etc/nginx/nginx.conf