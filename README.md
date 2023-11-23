# BackEnd-Bugs🪲

## Table Of Content:

- ### [Node.js](#nodejs-bugs)

- ### [Mongod And Mongodb Compass Bugs](#mongod-and-mongodb-compass-bugs)

- ### [Postman](#postman-bugs)

- ### [Unanswered Bugs](#unanswered-bugs) ☹️

- ### [Contribution](#contribution--1) 🤗

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
  

## Mongod And Mongodb Compass Bugs:

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
- Start `mongod` and make it active:
```bash
sudo systemctl start mongod
````
</details>

<details>
    <summary>
    IN UBUNTU : White Board in Mongodb Compass
    </summary>
    
### Issue:
  The problem is with the MongoDB Compass version.

### Solution:

```bash
wget https://downloads.mongodb.com/compass/mongodb-compass_1.39.3_amd64.deb
```

```bash
sudo dpkg -i mongodb-compass_1.39.3_amd64.deb
```

```bash
mongodb-compass
```

</details>
<details>
  <summary>
  IN UBUNTU: When Using Transaction Operation And Not run
    
  ![WhatsApp Image 2023-11-21 at 6 30 51 PM (1)](https://github.com/EmanMohamed36/BackEnd-Bugs/assets/74449080/b41d5cc0-4f09-496a-ad4a-10dbdbe08ab9)


  
  </summary>

### Solution:

  ```bash
  sudo apt-get install libkrb5-dev  
  ```
  ```bash
  npm install run-rs -g
  ```
  ```bash
  sudo systemctl stop mongod
  ```
  ```bash
  run-rs -v 4.0.0 --shell
  ```

</details>


## Postman Bugs:

## Unanswered Bugs:

## Contribution :

- ### If You Have a Bug 🪲 :- Make new Issue And We Will Response It
- ### If You Have an answer for Unanswered Bug :- Make Pull Request To View And Push Your Solve 💪
- ### Link Issue :https://github.com/EmanMohamed36/BackEnd-Bugs/issues/1 Show You How  To Contribute With Repo
