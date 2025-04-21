# Pipeline Execution Report

## Summary

This report outlines the steps taken to configure and execute the CI/CD pipeline for the Task API project.

## Steps

1. **Git Repository Management**  
     
- Initialized a local repository and connected it to GitHub.
``` git init ```
- add changes ``` git add .```
- commit changes ``` git commit -m "primer commit" ```
- connect  to remote github repository
    - ``` git remote add origin https://github.com/avargassot/pruebaModulo8.git```

    - ``` git branch -M main ```


   

2. **Docker Integration**  
     
   - Created a Dockerfile to containerize the application.
   - Build de image  ``` docker build -t prueba8_express .```
   - Execute containerize  ``` docker run -p 5000:5000 prueba8_express . ```

3. **Install dependencies Test**
    - Install Jest, supertest, eslint ```npm install jest supertest eslint -D ```

4. **Install Json Server**
    - Install dependencies ```json-server --watch db.json --port 5000```



   

3. **Jenkins Configuration**  
     
   - Configured Jenkins to automate the build, test, and deploy process.

## Issues Encountered

- \[Optional section for issues\]

## Results

- \[Add screenshots or logs of successful pipeline runs\]
1.  Init proyect Node and dependencies
![Node init](images/initNode.png)
2.  Git Remote
![Git remote](images/vinRep.png)
3.  install Json-Server
![Json Server](images/jsonServer.png)
4.  Api funcionando /users
![Api Funcionando ](images/apiFuncion.png)
Filter
![Api Funcionando ](images/ApiFuncionFilter.png)
5. Resultado Test Pipeline Jenkins
![Resultado Pipeline](images/ResTestPipeline.png)
6. Resultado Final 
![Resultado Pipeline](images/ResFinal.png)



