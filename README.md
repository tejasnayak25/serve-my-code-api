### Introduction
Serve-My-Code API lets you host your app's code on GitHub Repositories (including Private) and access them directly from your app, thereby providing security to the code.
##
## Currently, it is available for NodeJS only.
### Prerequisites
1) GitHub Account and Repositories
2) A token with read-only permissions to your respective repository.
3) A Code Editor, e.g, VSCode.

### Registration
Visit https://serve-my-code.onrender.com and login through GitHub.

### Creating a project
On login, you will be redirected to the dashboard.<br>
1) Click on new project
2) Enter the data 
3) Click on create

```
Package Name is the name of the package you're going to create.
Ex: com.packagename.apk.
App Name is the name of the app you're creating.
Ex: Example App
Token is the fine-grained token with read-only permissions to your repository which contains the code for your project (private or public).

Fill in the other details with respect to your project.
```

### Installation
Open your code editor.
Run this in the terminal after <code>npm init</code>.

Make sure the values of packageName, appName, author keys in your package.json file are exactly the same as the ones you entered while creating a project in https://serve-my-code.onrender.com/


```
npm i fetch-my-code
```

Create index.js file and put this snippet of code in the file.

```
require("fetch-my-code");
```

Your receiver-end is now ready.
Now, you just have to edit your repository and your app is automatically updated.

## Yep, this is it. No more leaking of code, no more mods, no more updates. Everything in your private repository.


### Notice
Coming soon for Python, PHP and other languages.
