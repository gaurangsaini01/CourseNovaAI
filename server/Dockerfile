FROM node:24-bookworm-slim
WORKDIR /server
COPY package*.json ./
RUN npm ci
COPY . .
ENV PORT=1234
EXPOSE 1234
CMD ["npm","start"]