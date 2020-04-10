FROM ubuntu:19.10

WORKDIR /workdir

RUN apt update && apt install -y nodejs npm git curl\
    && npm install -g npm-check-updates

# Initialization ( https://www.typescriptlang.org/docs/handbook/react-&-webpack.html )
# Generate pakcage.json and tscconfig.json
#RUN npm init -y \
#    && npm install --save-dev webpack webpack-cli\
#    && npm install --save react react-dom\
#    && npm install --save-dev @types/react @types/react-dom\
#    && npm install --save-dev typescript ts-loader source-map-loader
#    && npm install --save-dev webpack-dev-server
#    && npx tsc --init



