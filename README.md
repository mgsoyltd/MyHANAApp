# Getting Started

https://www.youtube.com/watch?v=yceqr9vycrs&list=WL

Welcome to your new project.

It contains these folders and files, following our recommended project layout:

File or Folder | Purpose
---------|----------
`app/` | content for UI frontends goes here
`db/` | your domain models and data go here
`srv/` | your service models and code go here
`package.json` | project metadata and configuration
`readme.md` | this getting started guide


## Next Steps

- Open a new terminal and run `cds watch` 
- (in VS Code simply choose _**Terminal** > Run Task > cds watch_)
- Start adding content, for example, a [db/schema.cds](db/schema.cds).


'''
cds build
npm run deploy
'''

## Learn More

Learn more at https://cap.cloud.sap/docs/get-started/.

## Start approuter
'''
cds bind --exec npm run app
'''

## Start and Stop Hana Cloud Service
'''
hana-cli start or hana-cli stop
'''

## Run the app

'''
npm run watch
cds bind --exec npm run app 
'''

## User-API
'''
http://localhost:5000/user-api/attributes
'''

## Call HDB Procedure 
'''
http://localhost:5000/catalog/sleep()
'''
