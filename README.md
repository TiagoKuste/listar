to run as executable:

on package.json:
"bin": {
    "listar": "index.js"
}

on index.js:
#!/usr/bin/env node

on terminal(project folder):
chmod +x index.js  // windows don't need this step
npm link

ready to run on terminal, just call listar(name can be changed) in any path, a path can be used as argument(listar ..)
