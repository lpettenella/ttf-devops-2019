FROM alpine
COPY index.js /app/index.js
RUN apk update && apk add npm
ENTRYPOINT ["node","/app/index.js"]
