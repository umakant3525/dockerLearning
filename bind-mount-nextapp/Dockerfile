FROM node:21
WORKDIR /bind-mount-nextapp
COPY package* .
RUN npm install
COPY . .
CMD ["npm", "run", "dev"]
