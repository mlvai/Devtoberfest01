# Getting Started

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
    - schemas && mock data  
`srv/` | your service models and code go here
    - service entities .cds , ui anotation -ui.cds  , Blogic .js
`package.json` | project metadata and configuration
`readme.md` | this getting started guide
`mta.yaml` |  deploy file
manual steps :
-   To avoid any loss of data, you change the MTA build parameters to remove all the CSV files and the hdbtabledata that  is generated by the CAP server out of the CSV files. Add the following line to the mta.yaml file 
- npx rimraf gen/db/src/gen/data


## Next Steps

- Open a new terminal and run `cds watch` 
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.
