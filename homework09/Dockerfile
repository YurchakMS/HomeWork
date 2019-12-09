FROM nginx:alpine
LABEL maintainer="m.yurchak@me.com"
RUN apk update && apk upgrade && apk add nginx 
CMD ["nginx", "-g", "daemon off;"]
