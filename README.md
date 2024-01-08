# AK Backend


  <b>Note:-</b> draw a model and decide the what are the store in data like : username, password<br>
-[Model link](https://app.eraser.io/workspace/YtPqZ1VogxGy1jzIDkzj) <br>

<h3><b>1) Production Setup</b> </h3><br>
i) npm init (in terminal-vscode).
<br>
ii) create a public folder and temp folder.
<br>

iii) create a .gitkeep file at temp folder.
<br>create a .gitgnore file.
<br>

iv) create -[gitignore generator](https://mrkandreev.name/snippets/gitignore-generator/) of node paste on .gitignore file.

v) create a .env and .env.sample file. <br>

vi) create a src folder. <br>
vii) In, create a folder by command - touch app.js constants.js index.js <br>

viii) In, package.json write a "type": "module" after description at line no. 5

<h3> Nodemon :</h3>
<br>
<h4>nodemon is a tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected.

nodemon does not require any additional changes to your code or method of development. nodemon is a replacement wrapper for node. To use nodemon, replace the word node on the command line when executing your script.</h4>

<h4 style="font-size: 23px">Installation</h4>
And nodemon will be installed globally to your system path.

You can also install nodemon as a development dependency:

npm i -D nodemon

<p>In package.json file change script "dev": "nodemon src/index.js"</p>

<h3>create a File</h3>
<p>mkdir controllers db middlewares models routes utils</p>

<h2>Pretier</h2>
<p>Prettier is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.</p>

<h3>Installation</h3>
npm i -D prettier

<p>create a .prettierrc file</p>
<p>In prettierrc ,

 {
    "singleQuote": false,<br>
    "bracketSpacing": true,<br>
    "tabWidth": 2,<br>
    "trailingComma": "es5",<br>
    "semi": true<br>
}</p>


<p>create a .prettierignore file</p>
<p>In prettierignore ,<br>
/.vscode<br>
/node_modules<br>
./dist<br>

*.env<br>
.env<br>
.env.*
</p>