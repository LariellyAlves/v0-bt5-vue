# v0-bt5-vue

Este projeto tem como objetivo apresentar informações sobre o curso de __Tecnologia em Sistemas para Internet (TSI) da UTFPR__. A base do site já havia sido iniciada previamente, porém foram realizados diversos ajustes em funcionalidades existentes, além da implementação de novas features para aprimorar a estrutura, usabilidade e apresentação do conteúdo.

## Alterações Realizadas

- Corrigido funcionamento do __dark mode__ pois anteriormente não estava funcionando em todas as abas do site.
- Ajustado as cores do __footer__ e __navbar__ para terem um destaque na página.
- Ajustado barra de pesquisa para não aplicar o dark mode e ser exibida de forma mais simples na página.
- Alterado o nome da página __Contato__ para __Fale Conosco__ pois acredito ter mais coerência com a página.
- Implementado novos textos nas paginas de __Início, Sobre e Fale Conosco__.
- Foi implementado novas palavras no arquivo de traduções para todos os textos que foram adicionados.
- Ajustado as cores das palavras do footer, pois estavam fora de padrão com o restante da página.
- Adicionado uma parte que representa a __matriz curricular__ do curso na aba __Sobre__.
- Ajustado as imagens que estavam na página para terem melhor qualidade de visualização.
- Adicionado o idioma __Francês__ na página para abrangir os alcances.




<details>
<summary>Passo a Passo do Trabalho</summary>

Projeto inicial para outros projetos com [__vue3__](https://vuejs.org/) e [__bootstrap5__](https://getbootstrap.com/)

O esperado de um projeto incial:
- [x] Mudar de tema (claro / escuro)
- [x] Fazer o auto do tema ???
- [x] Multi línguas ([vue-i18n](https://vue-i18n.intlify.dev/))
- [ ] Pensar no site com a pasta layouts?!?
- [ ] Busca interna ??? [algolia](https://www.algolia.com/developers) [typesense](https://typesense.org/)
- [ ] Blog / Notícias ???
- [ ] Mais frameworks CSS??? (beer, taywind)(templates)
- [ ] Mais modelos de rodapé e menu principal
- [ ] Colocar os ícones do bootstrap5
- [ ] Colocar mais palavras na tradução (i18n.json)


## Referências:
- [howbizarre](https://github.com/howbizarre/starter-template-vue-3-bootstrap-5-sass-dark-theme-typescript)
- [danielschmitz - kitchenStock](https://github.com/danielschmitz/kitchenStock-vue3)
- [danielschmitz - vue3-book](https://github.com/danielschmitz/kitchen-app-vue3-book)
- [danielschmitz - livro vue3 grátis](https://leanpub.com/book-vue-br)

## Preparando o ambiente de desenvolvimento (vscode):
Instalar o [vscode](https://code.visualstudio.com/Download) com os plugins:
- [Vue - official - Prioridade!!!](https://marketplace.visualstudio.com/items?itemName=Vue.volar)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Console Ninja](https://marketplace.visualstudio.com/items?itemName=WallabyJs.console-ninja)
- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)



## Como começar

Crie um novo repositório a partir do modelo e use seu gerenciador de pacotes favorito para instalá-lo. Utilizando NPM os comandos são:

### Install

```bash
npm install
```

### Ambiente de Desenvolvimento

```bash
npm run dev
```

### Build

Certifique-se de que todas as configurações revisadas sobre o script de construção estejam no arquivo package.json e nos arquivos .env.[mode].

```bash
npm run build
```
