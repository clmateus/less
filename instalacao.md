# Instalação do Less

1. npm init
2. npm install -g less
3. npm install --save-dev less
4. script package.json: "less": "lessc ./src/styles/main.less ./build/styles/main.css"
5. npm i -g less-watch-compiler

# Instalação plugins Less

1. npm i --save-dev less-watch-compiler
2. script package.json: "less": "less-watch-compiler ./src/styles ./build/styles main.less"