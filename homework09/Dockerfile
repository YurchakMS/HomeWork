FROM nginx:alpine
LABEL maintainer="m.yurchak@me.com"
RUN apk update && apk upgrade && apk add nginx 
ADD index.html /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;"]
