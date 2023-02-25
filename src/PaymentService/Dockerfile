FROM node:14.21.3-bullseye-slim

WORKDIR /app
COPY . .
ENV PORT=80
RUN npm install
CMD ["npm","start"]