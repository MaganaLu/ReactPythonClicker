# ReactPythonClicker
Clicker game with react and python using pyreact.
This was a project for fun to see how the react python wrapper worked. I also wanted to get more confortable using python. 

must create a python virtual env
1. python -m venv venv (Windows)
2. venv\Scripts\activate
3. pip install transcrypt

then react
1. npm init -y
2. npm install parcel-bundler --save-dev
3. npm install parcel-plugin-transcrypt --save-dev

then react libraries
1. npm install react@16 react-dom@16
2. replace ./node_modules/parcel-plugin-transcrypt/asset.js with included asset.js file

Then start up parcel dev webserver 
1. npx parcel --log-level 4 --no-cache index.html

app will be hosted at http://localhost:1234


