FROM node:alpine
WORKDIR /usr/src

# Copy Package Directories
COPY package.json .
COPY yarn.lock .

# Install inside Container
RUN yarn install

# Copy Remaining Files
COPY . .

CMD ["yarn", "serve"]