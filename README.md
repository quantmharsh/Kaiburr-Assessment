# Kaiburr-Assessment(Harsh Srivastava VIT ,vellore)



<b>Dependencies Used</b><br/>
1. Web<br/>
2. DevTools<br/>
3. Lombook<br/>
4. Swagger<br/>
5. MongoDB<br/>
6. Thymeleaf<br/>

<b>Task 1 & Task 4</b><br>
used springboot for completing task<br/>
endpoints<br/>
1. /add (Add the details to the database) <br/>
2. /getById (Retrive the data using ID) <br/>
3. /getByName ( Retrive the Data using name) <br/>
4. /deleteById (Delete from the Database using ID) <br/>

 Rest API's postman:<br/>
1. /addServer <br/>
2. /findByName <br/>
3. /findByID <br/>
4. /deleteByID <br/>

<b>Controller: /Server/src/main/java/com/spring/test/controller</b><br/>

<b> Task 3 </b></br>
To Run in docker.</br>
Open terminal</br>
Go to Server/target </br>
And run <i>docker build . -t server </i> </br>
This will create a image of the JAR file. </br>
Now run the docker-compose.yml using <i> docker-compose up. </i> </br>
Now using web Browser at localhost:8086 we can use the endpoints.</br>

<b> Task 2 </b></br>
To create the Swagger API is Used the online edittor. And downloaded the code as Server for Spring. But was unable to make it work. So I Have upload the YAML file which I was able to create. </br>

<b>Screenshots</b><br>

1. /add : add details<br/>
<img src="Screenshots/Docker/1)%20Add%20the%20data.png"> <br/>

2. /done :data inserted <br/>
<img src="Screenshots/Docker/2)%20Confirmation%20of%20data.png"> <br/>

3. /getById : server details using id <br/>
<img src="Screenshots/Docker/3)%20Find%20by%20id.png"> <br/>

4. /deleteById : delete using ID <br/>
<img src="Screenshots/Docker/7)%20Delete%20by%20id.png"> <br/>
5. /getByName :  getserver details usingName <br/>
<img src="Screenshots/Docker/5)%20Find%20by%20name.png"> <br/>



