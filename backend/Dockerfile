FROM node:17.9.0-slim
LABEL maintainer="sunil"
RUN useradd backend
WORKDIR /backend
COPY . .
RUN npm run backend
EXPOSE 3000
USER backend
CMD ["npm","start"]