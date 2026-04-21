本地部署：
前端: node版本14
npm install 安装依赖
后端：配置redis服务 


docker 部署
前端 生成dist文件夹 npm install npm run build:prod
后端 生成jar包 mvn clean package -DskipTests
docker-compose up --build
