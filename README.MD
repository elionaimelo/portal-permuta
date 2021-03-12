
## 📝 Table of Contents

- [Pré-requisitos](#pre-requisitos)
- [Deployment](#comandos)

## 🏁 Pré-requisitos <a name = "pre-requisitos"></a>

node [https://nodejs.org/download](https://nodejs.org/download/).
gulpjs [https://gulpjs.com/](https://gulpjs.com/)

> **Gulp:** é uma ferramenta de automação de tarefas em JavaScript. Tarefas como minificar, otimizar e compilar arquivos, tão repetitivas e necessárias ao desenvolvimento, podem ser automatizadas com o Gulp. As tarefas do gulp são encontradas em gulpfile.js.

### Instalar gulp globalmente

Para instalar o gulp, execute o seguinte comando:

```
npm install --global gulp-cli
```
Depois execute o comando para instalar todas as outras dependências do projeto. 

```
npm install
```

Essas dependências ficam no package.json. Se caso for usar alguma biblioteca e ela for instalada via linha de comando(usando o npm) use a tarefa de javascript que se encontra no arquivo gulpfile para adicioná-la ao projeto.js, ela pode ir para o diretório lib ou não, você escolhe


Os arquivos html estão divididos em partes para facilitar a manutenção, assim como os de sass. Com o comando gulp eles serão concatenados e colocados no diretório dist

O diretório **src** é responsável por tudo que está editável no projeto, ou seja, as imagens sem otimização, scripts e estilos que não estão concatenados

O diretório **dist** é o local que está tudo que foi otimizado, concatenado e etc.

o arquivo **.editorconfig** apenas padroniza os estilos dos seus códigos seja em editor de texto ou IDE 

Para o css será utlizado Sass, uma outra forma de escrever css. O gulp irá nos ajudar a minificar e concaternar o css para deixar a página mais leve, assim como também os scripts

## 🚀 Alguns comandos para o projeto <a name = "comandos"></a>


+  `gulp` - recompila e minifica tudo e coloca dentro do diretório `dist`. Além de iniciar uma servidor local com browserupdate

+  `gulp build` - recompila e minifica tudo e coloca dentro do diretório `dist`
