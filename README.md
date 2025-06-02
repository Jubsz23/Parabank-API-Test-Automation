<img width=100% src="https://capsule-render.vercel.app/api?type=rect&height=300&color=gradient&text=Parabank-nl-API%20Test%20Automation&textBg=false&fontAlign=50&section=header"/>
<div align="left" />
   
# REST API

<div align="center" >
  <img src="https://www.svgrepo.com/show/354202/postman-icon.svg" alt="Postman" width="100"/>
</div>

## Description
This project contains a collection of API tests created with Postman. It is used to test and validate the endpoints of a RESTful application.
<br> </br>
 ### 🛠️ Tech Stack:

![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat&logo=postman&labelColor=FFFFFF)
![javascript](https://img.shields.io/badge/-javascript-F7DF1E?style=flat&logo=javascript&labelColor=0D1117)
![Bdd](https://img.shields.io/badge/-BDD-23D96C?style=flat&logo=cucumber&labelColor=FFFFFF)
![GitHub](https://img.shields.io/badge/-GitHub-545454?style=flat&logo=github)

## Project Structure
- **Collections**: Contains the Postman request collections.
- **Environments**: Environment files for different configurations (development, testing, production).
- **Scripts**: Pre-request and test scripts to automate tasks.

## Requirements
- [Postman](https://www.postman.com/downloads/)
- [Newman](https://github.com/postmanlabs/newman) (for command-line execution)
- [Node.js](https://nodejs.org/en/download/package-manager) (to install Newman)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/project-name.git
   ```
2. Navigate to the project directory:
 ```bash
cd project-name
```
## Usage

### Postman

1. Import the collection and environment into Postman. <br>
2. Configure the environment as needed. <br>
3. Run the collection. <br>

### Newman
1. Install Newman:
```yaml
npm install -g newman
```
2. Install newman-reporter-htmlextra:
```yaml
npm install -g newman-reporter-htmlextra
```
3. Run the collection using Newman with the htmlextra reporter:
```yaml
newman run collections/your-collection.json -e environments/your-environment.json -r htmlextra
```

## Contributing
Contributions are welcome! Feel free to open issues and pull requests.

## Comments:

  - It was used step nomenclature in the Camel Case standard;

  - It was used describe and it nomenclature in a clear and objective way;

  - It was configured the project for low Chrome consumption in e2e settings;

  - It was used commands as a good practice to code the scenarios below.
    
  - The project wiki details the testing strategies used for this project, as well as possible improvements.<br>
  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;👇🏾 👇🏾 👇🏾 <br>
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <a href="https://github.com/Jubsz23/Parabank-API-Test-Automation/wiki" target="_blank"><img src="https://img.shields.io/badge/-GitWiki-%23333?&style=flat&logo=github" target="_blank"></a>



