# Welcome to [TMDB](https://www.themoviedb.org/) API Reference Docs👋
This is my capstone project for Technical Writing Mentorship Program [TWMP](https://technicalwritingmp.com/) API docs cohort, a revamp of The Movie Database [TMDB](https://www.themoviedb.org/) API reference docs. <br/>
**Link to revamped docs**: [Revamped TMDB Docs](https://devliz.mintlify.app/introduction)
*********************************************************************************************************************************************************************************
*********************************************************************************************************************************************************************************

## About The Movie Database (TMDB)
The Movie Database (TMDB) is a community-built database for movies and TV shows. Its API allow users to get information about movies, TV shows, movie professionals etc.
Some of its use cases include:
- Finding Movies and TV Shows
- Getting Movie recommendations
- Contributing to the database
- Developing applications
*********************************************************************************************************************************************************************************
*********************************************************************************************************************************************************************************
## About the project
This documentation project is designed to improve on the existing [TMDB Documentation](https://www.themoviedb.org/). The new documentation features include:
- A simple and user-friendly interface
- A snapshot of the key conceptual pages
- A well-designed navigation and information architecture
- A well-structured reference guide
- A set of well-defined endpoints
*********************************************************************************************************************************************************************************
*********************************************************************************************************************************************************************************

## Tools used
The major tools used for this project include:
- **Postman:** For testing and exporting endpoints
- **Postman-to-OAS converter:** For converting Postman OpenAPI Spec (OAS) file to YAML.
- **Swagger and VS Code:** For editing the OAS file
- **Mintlify:** For building and customizing the documentation.
  
*********************************************************************************************************************************************************************************
*********************************************************************************************************************************************************************************

### To run this documentation locally:
**1. Fork the repository (if you're not sure, [here's how](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)**  

**2. Clone your forked repository to your local computer using this command** 
```
git clone https://github.com/your-username/docs.git
cd docs.git
```

**3. Install dependencies** <br/>
*Ensure to have Node.js version 19+ installed*
*Then use the command below to install the Mintlify CLI and project dependencies:*
```
npm install -g mintlify
mintlify install
```

**4. Start development server** <br/>
*Run the command below to start the development server. This will serve the documentation at http://localhost:3000 by default.*
```
mintlify dev
```
**5. Edit and preview changes** <br/>
Make your changes to the documentation files inside the project folder.
*Mintlify server will automatically reload changes.*

***For a BTS of the documentation process, please check below.***
*********************************************************************************************************************************************************************************
*********************************************************************************************************************************************************************************


<br/>

## The Process

1. ### Existing Docs Audit
   To improve on the existing TMDB documentation, I did an audit to understand its strengths and weaknesses, I also discussed with possible users (developers) to understand their pain points. From my audit, the documentation needed an improvement on Information architecture and overall user experience.
   
   ![image](https://github.com/user-attachments/assets/b0912734-3ba0-4b2e-85a1-d781c3b7d0dd)


3. ### Testing the Endpoints with Postman
   I tested the 100+ endpoints on TMDB platform (using [Postman](postman.com)) to ensure that they were not broken or incorrect in any way.

   https://github.com/user-attachments/assets/adcca91d-d356-4b58-a120-baf2d8b3aeca


4. ### Exporting to OpenAPI Spec
   After a successful test of all the available endpoints on Postman, I used the Postman export feature to convert the API references to an OpenAPI spec file. I further converted the exported json file into yaml, using [TWMP](https://technicalwritingmp.com/)'s OpenAPI spec converter. I edited the converted YAML file to add the necessary descriptions and components, using [Swagger editor](https://editor.swagger.io/) and the VS Code IDE.
   
   ![oas-edit](https://github.com/user-attachments/assets/1eae03c1-3964-4de9-8ced-3b148479ba7c)


6. ### Building the docs on Mintlify
   For the final phase of this project, I used the [Mintlify](https://mintlify.com/) documentation tool to bring the OpenAPI reference to life. I imported the API reference from the OpenAPI spec file, customized the look and feel of the documentation, and improved its overall user experience using Mintlify components and custom CSS.
   
   ![image](https://github.com/user-attachments/assets/0d360eab-3857-40ae-9c67-b4d87ccf0f41)

### Link to final documentation
[Revamped TMDB Docs](https://devliz.mintlify.app/introduction)

