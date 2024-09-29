### Day 1 Assignments

> [!NOTE]
> Pls edit this table while submitting the assignments

| Status         | Questions     | 
|----------------|---------------|
| <ul><li>- [x] </li></ul> | Execute 25 Docker CLI commands, capture the output screenshots, and document each command's usage on a GitHub Wiki page. |
| <ul><li>- [x] </li></ul> | Install VSCode and Python. Check the version of Python. Document these steps in GitHub Wiki. |
| <ul><li>- [x] </li></ul> | [Python] Create a sample flask app and edit the same to showcase your college information(Name, Register_number,etc) |
| <ul><li>- [x] </li></ul> | [Docker] Create the docker image for the above-mentioned flask app and run the same view of the page in a browser |
| <ul><li>- [ ] </li></ul> | [Docker] Create a docker compose file for the 2 images: nginx/httpd and run the same view of the page in a browser |
| <ul><li>- [ ] </li></ul> | [Docker] Pull one of the participant’s docker images and verify whether the app is running or not  |
| <ul><li>- [ ] </li></ul> | Create a GitHub account with a personal mail ID & fork this repo and rename this in the format 22AM0XG-Assignments-Register-Number  |
| <ul><li>- [ ] </li></ul> | Create a LinkedIn account with personal mail ID  |

***

### Day 1 Assignments - Answers and Screenshots

> [!WARNING]
> Pls submit the correct screenshots

> [!CAUTION]
> Pls don't copy from others. Marks will be reduced for both students

#### #1 Execute 25 Docker CLI commands, capture the output screenshots, and document each command's usage on a GitHub Wiki page

docker version
![image](https://github.com/user-attachments/assets/c6a11dbd-e0a8-411e-bf15-8731678de19f)

docker info
![image](https://github.com/user-attachments/assets/cd6f48de-b09b-472f-9d84-4f39303789d8)

docker system info
![image](https://github.com/user-attachments/assets/2822b684-d1b3-446c-bdbd-9203d74aaecb)

docker --help
![image](https://github.com/user-attachments/assets/037330b9-05c1-4792-ab85-3f8a49ec430a)

docker compose version
![image](https://github.com/user-attachments/assets/94dcf012-2955-4cba-a34f-d55b2d871b60)

docker login
![image](https://github.com/user-attachments/assets/f1eb99d5-ae60-4255-b60a-40ca59d4e457)

docker logout
![image](https://github.com/user-attachments/assets/e0334bba-946d-497e-bd2c-ad8c59db0e52)

docker search nginx
![image](https://github.com/user-attachments/assets/30658559-bf4e-4484-9762-4c99b028b0cd)

docker images
![image](https://github.com/user-attachments/assets/56f9f01c-f5ac-47e9-afe9-f0fefc8870b1)

docker docker pull nginx
![image](https://github.com/user-attachments/assets/c7ae6297-8109-41f8-90b4-93194ec9d385)

docker run -idt nginx
![image](https://github.com/user-attachments/assets/bd047b26-9d0c-4cec-98a8-a2b01dfaf32b)

docker ps 
![image](https://github.com/user-attachments/assets/c2ff31da-c87a-49d0-b037-7a37f66033e3)

docker stop
![image](https://github.com/user-attachments/assets/3d5a1d44-5ec7-45c7-bf55-06d724c7214f)

docker start
![image](https://github.com/user-attachments/assets/36b1613c-5e7f-4182-a6a4-26a5392c93b5)

docker restart
![image](https://github.com/user-attachments/assets/dad0c8c7-a0c6-4ff9-b04b-583ed8a00dc7)

docker logs
![image](https://github.com/user-attachments/assets/c6b82fd7-73fe-4040-acde-ec5c1e9786ab)

docker rm
![image](https://github.com/user-attachments/assets/e62af8ac-45dd-4ba2-a127-78f3cc0bd05d)

docker build
![image](https://github.com/user-attachments/assets/331d5bfd-c385-4c0f-bb5c-19663c133cbd)

docker push
![image](https://github.com/user-attachments/assets/900fd72e-8bac-446e-80d3-8e0d1b2b7860)

docker tag 
![image](https://github.com/user-attachments/assets/8da6e001-062a-4379-82c7-23c3c61d35a4)

docker save
![image](https://github.com/user-attachments/assets/505ce089-6a3c-4e2d-9cf6-7532cd676915)

docker load
![image](https://github.com/user-attachments/assets/09822212-bc06-49d4-9158-a4f50487272f)

docker exec
![image](https://github.com/user-attachments/assets/f2edf143-2991-4086-919b-1444472ae03b)

docker cp
![image](https://github.com/user-attachments/assets/205eb513-aa70-4aac-a807-185052713f27)

docker system prune
![image](https://github.com/user-attachments/assets/07c2a040-225f-4905-8f65-ccd8add27a86)


***

#### #2 Install VSCode and Python. Check the version of Python. Document these steps in GitHub Wiki

python --version
![image](https://github.com/user-attachments/assets/6b60b799-558a-4907-96ac-d46e67902d16)

***

#### #3 [Python] Create a sample flask app and edit the same to showcase your college information(Name, Register_number,etc)

python helloworld.py
![image](https://github.com/user-attachments/assets/5e5102c5-b8a5-4ebb-8ab9-4a733e600158)

python app.py
![image](https://github.com/user-attachments/assets/cc475633-a0c6-4ec2-8ead-42c3fb9419bd)

***

#### #4 [Docker] Create the docker image for the above-mentioned flask app and run the same view of the page in a browser

docker build
![image](https://github.com/user-attachments/assets/d6cf0968-d54b-4775-9fc2-c04c19f52c9a)

docker push
![image](https://github.com/user-attachments/assets/4c3654a4-0210-4bae-8d33-b5666a149b1a)

***

#### #5 [Docker] Create a docker compose file for the 2 images: nginx/httpd and run the same view of the page in a browser

docker compose 
![image](https://github.com/user-attachments/assets/98e08daf-3952-4855-a430-fc8ab2651e78)
![image](https://github.com/user-attachments/assets/85396515-251f-4bb1-a33c-2afa185c8c58)

***


#### #6 [Docker] Pull one of the participant’s docker images and verify whether the app is running or not

docker run 
![image](https://github.com/user-attachments/assets/2162df22-05c1-4173-91c8-0a2c6cb0eeec)

***

#### #7 Create a GitHub account with a personal mail ID & fork this repo and rename this in the format 22AM0XG-Assignments-Register-Number
> Add your answer here!

***

#### #8 Create a LinkedIn account with personal mail ID
> Add your answer here!

***
