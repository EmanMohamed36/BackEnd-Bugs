# BackEnd-Bugs🪲


## Table Of Content:

- ### [Node.js](#nodejs-bugs)

- ### [Mongod And Mongodb Compase Bugs](#mongod-and-mongodb-compase-bugs)

- ### [Postman](#postman-bugs)

- ### [Unanswered Bugs](#unanswered-bugs) ☹️

- ### [Contribution](#contribution) 🤗

  

## Node.js Bugs:
<details>
      <summary>
      Error [ERR_MODULE_NOT_FOUND]: Cannot find module in JS
      </summary>
  
      
      when you set the "type" attribute to "module" in your package. json file:
  #### but the file extension when importing
  #### ex:
  #### import {sum} from './another-file'  "wrong"
  #### import {sum} from './another-file'  "right"
  
</details>

## Mongod And Mongodb Compase Bugs:

<details>
  
  <summary>  
  Connection Error!!
    
  ![WhatsApp Image 2023-11-22 at 10 40 08 PM](https://github.com/EmanMohamed36/BackEnd-Bugs/assets/74449080/8cb4ef73-c407-4719-999e-a78d998d34ff)

  </summary>
  
  - ### IN WINDOWS:
    ```
    Press the Windows + R    
    ```
    ```
    Type services.msc and hit Enter
    ```
    ```
    Search MongoDB.exe. Right click on it and select Start
    ```
- ### IN UBUNTU:

  - Make Sure Your Mongod is run Successfully:
    ```bash
    Mongod
    ```
  - Start Mongod And Make it Active

    ```bash
    sudo systemctl start mongod
    ```

</details>

<details>
    <summary>
    IN UBUNTU : White Board in Mongodb Compass
    </summary>
    
#### The Problem in Mongodb Compass Version 
``````bash
wget https://downloads.mongodb.com/compass/mongodb-compass_1.39.3_amd64.deb
``````
``````bash
sudo dpkg -i mongodb-compass_1.39.3_amd64.deb
``````
``````bash
mongodb-compass
``````

</details>

## Postman Bugs:

## Unanswered Bugs:

## Contribution :
- ### If You Have a Bug 🪲 :- Make new Issue And We Will Response It
- ### If You Have an answer for Unanswered Bug :-  Make Pull Request To View And Push Your Solve  💪
