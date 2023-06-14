FROM node:17.9.0-slim
LABEL maintainer="sunil"
RUN useradd frontend
WORKDIR /frontend
COPY . .
RUN npm run frontend
EXPOSE 3001
USER frontend
CMD ["npm","start"]