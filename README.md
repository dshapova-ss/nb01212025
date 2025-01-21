# Useful links
[Dockerfile](https://github.com/dshapova-ss/nb01212025/blob/main/Dockerfile) <br/>
Full trivy scan folder before/after fix

## Trivy scans screenshots
before fixes
![Screenshot 2025-01-20 192042](https://github.com/user-attachments/assets/b380b4bd-b494-493f-8e0f-d99f2ed8b279)
![Screenshot 2025-01-20 192058](https://github.com/user-attachments/assets/a16cce1d-d433-4dba-872c-5a3fabba8326)

after fixes
![image](https://github.com/user-attachments/assets/d3985581-2e87-4184-b72c-bc5cd7c51ff8)

## Azure Portal properties screenshot
![Screenshot 2025-01-21 121924](https://github.com/user-attachments/assets/4b977d1f-79cc-4c8a-bf0c-78586553dcf3)
![Screenshot 2025-01-21 122452](https://github.com/user-attachments/assets/a4298281-d3b0-4378-8a5a-698eb820a0be)
![Screenshot 2025-01-21 122503](https://github.com/user-attachments/assets/e9b5bbd5-8fcc-4af6-8c8d-35dfa9d43fea)
![Screenshot 2025-01-21 122538](https://github.com/user-attachments/assets/5da21228-8205-46c1-b328-dcf362d94363)
![Screenshot 2025-01-21 122603](https://github.com/user-attachments/assets/d97aaf51-9d36-4292-9962-147e332f6eaf)


## Ready-steady-go
The steps to run are:
1. clone this tool: `git clone https://github.com/dshapova-ss/nb01212025.git` 
2. cd into the folder: `cd nb01212025`
3. Build a docker image: `docker build . -t webapp:latest`
4. Run a container with: `docker run --rm -it -p 8080:80 -d webapp`
5. Open your browser and navigate to: `localhost:8080`

