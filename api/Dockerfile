FROM node:16
RUN mkdir /backend
WORKDIR /backend
COPY . /backend
RUN npm install
RUN npm run build
EXPOSE 8080
CMD ["sh", "-c", "npx prisma db push && node build/index.js"]
