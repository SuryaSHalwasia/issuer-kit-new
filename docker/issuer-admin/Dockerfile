FROM docker.io/node:hydrogen
WORKDIR /app
COPY issuer-admin/package*.json ./
RUN npm install
COPY issuer-admin/ .
RUN npm run build
