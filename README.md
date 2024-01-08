1. install docker and Docker-compose
```
sudo apt install docker.io docker-compose -y
```

2. clone repo
```
git clone https://github.com/AbhishekUnOfficial/dns-setup/ && cd dns-setup
```
3. fill up .env file
```
sudo nano .env
```
4. make acme.json file
```
mkdir -p letsencrypt
```
5. touch acme.json
```
touch letsencrypt/acme.json
```
6. give permission
```
chmod +x letsencrypt/acme.json
```
7. run Docker-compose
```
sudo docker-compose up -d
```
