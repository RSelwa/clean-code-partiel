FROM alpine:3.14

WORKDIR /home
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD npm run dev