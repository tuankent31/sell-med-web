### be-site
- run: docker-compose up
- docker file: 
docker build -t api-springboot-service . 
docker run -d -ti -p 8080:8080 --name api-springboot-service  api-springboot-service

### fe-site
- install packages: npm install
- run the app: npm start
- open [http://localhost:3000](http://localhost:3000) to view