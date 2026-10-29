# Portfólio — Rafael

🔗 **Site no ar:** https://SEU-USUARIO.github.io

Portfólio pessoal que mostra automaticamente meus projetos públicos do GitHub.
Os dados vêm da API do GitHub cada vez que alguém abre a página, então
qualquer projeto novo aparece sozinho, sem precisar editar o site.

## Como funciona

- **Perfil:** nome, foto e bio vêm de `api.github.com/users/SEU-USUARIO`
- **Projetos:** lista dos repositórios públicos (forks ficam de fora), ordenados por estrelas
- **Links:** se o repositório tem o campo *Website* preenchido, o card leva para ele; se não, leva para o código no GitHub

## Tecnologias

- HTML, CSS e JavaScript puro, sem framework e sem build
- [GitHub REST API](https://docs.github.com/rest)
- Hospedagem no [GitHub Pages](https://pages.github.com)

## Rodando localmente

Basta abrir o `index.html` no navegador. Não precisa instalar nada.

## Personalizando

| O que mudar | Onde |
|---|---|
| Usuário do GitHub | constante `USER` no `index.html` |
| Mostrar só alguns projetos | adicione o tópico `portfolio` nos repositórios e ative o filtro comentado no script |
| Cores e layout | bloco `<style>` no `index.html` |

## Contato

- GitHub: [@SEU-USUARIO](https://github.com/SEU-USUARIO)
- LinkedIn: *adicione aqui*
- E-mail: *adicione aqui*
