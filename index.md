## Introdução

O projeto é desenvolvido utilizando o NodeJS com ElectronJS. É necessário baixar o Node disponível em:
https://nodejs.org/en/download/ 

o que é NodeJS?
É um compilador javascript que permite a utilização da linguagem em qualquer segmento (apps executáveis, RESTApi's, Spa's, Nativos Mobile, etc...). Ao instalá-lo, ele agrega um Package Manager chamado NPM

O que é NPM?
É um Package Manager que faz a gestão das ferramentas utilizadas no projeto.

O que é ElectronJS
É uma biblioteca que compila um código Javascript em um executável

Com o nodejs instalado, abra o CMD para execução dos comandos.

Abra a pasta do projeto pelo CMD, e instale as bibliotecas necessárias do projeto (no caso, ElectronJS) digitando o comando: npm install

Execute o projeto localmente utilizando o comando: npm start

Para compilar o projeto em um executável, é necessário instalar globalmente a biblioteca "electron-packager" via o comando: npm install electron-packager -g

Em seguida, na pasta do projeto, execute o comando:
electron-packager ./ robo --platform=win32 --arch=x64

Será gerado um executável da aplicação





## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/costdrivers/docs/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/costdrivers/docs/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
