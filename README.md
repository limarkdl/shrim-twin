# ShrimTwin - Robot System Digital Twin
![shrimtwin-banner](https://github.com/user-attachments/assets/63812a93-3b3b-40e7-8ec2-9dcf3f7b7467)

## About:

This project is an interactive dashboard for robot systems that allows to monitor current state of robots and smart devices 

![Ivan_Kostin_Poster_21078541](https://github.com/user-attachments/assets/08b42140-b33e-4347-960a-df5e31491efa)


### Appearance
[Figma design file](https://www.figma.com/design/jdrHEUwNXowV4hHIZrkSP5/Shrim-Twin?node-id=0-1&t=hKQjofC8kiQhJF6H-1)
<details>
  <summary>DESIGN MOCKUP</summary>
  
![appearance](https://github.com/user-attachments/assets/8bf77216-de8f-468f-9c2e-5b4b64899616)

</details>

### Pulling Docker image 
1. Pull the `limarkdl/shrim-twin` image:
```bash
docker pull limarkdl/shrim-twin
```  
2. Run the pulled image:
```bash
docker run -p 3000:3000 limarkdl/shrim-twin
```
3. Open `http://localhost:3000` in your browser
   
### Running DEV 

1. Install all required dependencies:

```bash
npm run i
```

2. For development version run:

```bash
npm run dev
```

### Running PRODUCTION

1. Build the image 
```bash 
docker build -t <your_desired_name> .
```
2. Run the image
```bash
docker run -p 3000:3000 <your_desired_name>
```
4. Now this application is available at `http://localhost:3000`

### Required GitHub secrets
- `DOCKERHUB_USERNAME` - username of your DockerHub account
- `DOCKERHUB_TOKEN` - access token for your DockerHub
- `MY_GITHUB_TOKEN` - access token for your GitHub


#### By Ivan Kostin, [@limarkdl](https://github.com/limarkdl)
