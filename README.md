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
  ### Issue:
  The file extension is required when importing.
  
  ### Solution:
  Use the correct file extension when importing.
  
  #### Incorrect:
  ```javascript
  import { sum } from './another-file';
  ```
  
  #### Correct:
  ```javascript
  import { sum } from './another-file.js';
  ```
  
</details>

## Mongod And Mongodb Compase Bugs:

<details>
  
  <summary>  
  Connection Error!!
    
  ![WhatsApp Image 2023-11-22 at 10 40 08 PM](https://github.com/EmanMohamed36/BackEnd-Bugs/assets/74449080/8cb4ef73-c407-4719-999e-a78d998d34ff)

  </summary>
  
  ### Windows:
  - Press the Windows + R
  - Type `services.msc` and hit Enter
  - Search `MongoDB.exe`, right-click on it, and select Start

  ### Ubuntu:
  - Make sure `mongod` is running successfully: `mongod`
  - Start `mongod` and make it active: `sudo systemctl start mongod`
</details>

<details>
    <summary>
    IN UBUNTU : White Board in Mongodb Compass
    </summary>
    
### Issue:
  The problem is with the MongoDB Compass version.

### Solution: 
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
