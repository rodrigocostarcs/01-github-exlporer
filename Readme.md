Projeto Iniciado
-primeira coisa a se fazer em um projeto usando javascript ou react js é iniciar o package.json com o "yarn init -y"
- instalar o react "yarn add react"
- instalar o react-dom "yarn add react-dom" (trabalhar com react na web, HTML convertido em uma sintaxe de objetos)
- instalar o babel "yarn add @babel/core @babel/cli @babel/preset-env -D" - @babel/preset-env identifica o ambiente que está sendo executado o babel para converter o código da melhor maneira possível. - @babel/cli permite a execução por linhas de comando. - @babel/core possui todas bibliotecas do babel.
- Após instalar o babel é necessário criar o arquivo de configuração 'babel.config.js' e exportar o preset-env.
  - yarn babel src/index.js --out-file dist/bundle.js (maneira para chamar o babel e converter o arquivo js com o babel)
- instalar o babel para reconhecer código react "yarn add @babel/preset-react -D"
- ".jsx" é a nomenclatura para quando usamos código html dentro de arquivos JS.
