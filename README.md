# CRUD - Vite App

##### This app was developed using Vite and a modular structure. Some of the implemented topics include:

* Async/Await
* Promises
* Fetch
* Render

### Develop mode:

1. Create .env file or copy the .env.template and rename it to .env

2. Modify the variables adding your url

# Preliminary settings:

~~~ bash
npm install

npm i json-server -D

npm run dev
~~~

To add the following command in the script section of the package.json file (the port is optional), make modifications as follows:

```json
"server": "json-server server/db.json --port 3001"
```

Finally execute the following script to run the json-server

```bash
npm run server
```

Regards.