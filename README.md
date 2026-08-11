# 📝 Blog pessoal e Portfólio

[![Deploy](https://github.com/henriquesebastiao/blog/actions/workflows/deploy.yml/badge.svg)](https://github.com/henriquesebastiao/blog/actions/workflows/deploy.yml)
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fhenriquesebastiao.com%2F)](https://henriquesebastiao.com)
[![GitHub Release](https://img.shields.io/github/v/release/henriquesebastiao/blog?color=blue)](https://github.com/henriquesebastiao/blog/releases)
[![GitHub License](https://img.shields.io/github/license/henriquesebastiao/blog?color=blue)](https://github.com/henriquesebastiao/blog/blob/main/LICENSE)

Link: [https://henriquesebastiao.com](https://henriquesebastiao.com)

A ideia aqui é ter um lugar sob o meu controle, onde eu possa compartilhar meus pensamentos, percepções e devaneios.
Já há algum tempo em que venho cogitando a abordagem que mais me agradasse para escrever meus posts,
depois de algum tempo testando essa implementação com Jekyll cheguei a conclusão de que vou seguir por esse caminho.
Primeiro porque escrever em Markdown me é agradável e simples, mas principalmente porque é portável.

### Jekyll

Este site é construído com [Jekyll](https://jekyllrb.com/) usando o tema [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) como base.
Fiz algumas customizações no tema, as principais estão listadas abaixo.

#### Front Matter dos posts

- `image` - imagem que será a pré-visualização ao compartilhar URL do post.
- `post_image` - imagem principal que aparece no início da pastagem e no card do post na página home.
- `scripts` (lista) - adiciona arquivos JavaScript customizados ao head da página.
- `styles` (lista) - adiciona arquivos CSS customizados ao head da página.

#### Internacionalização

Os páginas possuem tradução para o inglês, usando o plugin [Polyglot](https://polyglot.untra.io/).

### Construindo

Para instalar as dependências de desenvolvimento, siga os seguintes passos:

1. Instale o `ruby` e o `rubygems`.
2. Instale o `bundler` com o comando:

```shell
gem install bundler
```

3. Configure o bundler para instalar as dependências do projeto na pasta do projeto:

```shell
bundle config set --local path '.bundle'
```

4. Instale as dependências:

```shell
bundle install
```

5. Por fim inicialize a aplicação:

```shell
bundle exec jekyll s -l
```
