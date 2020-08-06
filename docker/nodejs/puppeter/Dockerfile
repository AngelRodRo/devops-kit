FROM buildkite/puppeteer:latest

COPY package*.json ./

RUN npm install

COPY . .

CMD ["node", "index.js"]