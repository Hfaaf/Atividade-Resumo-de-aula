## GIT, GITHUB & VSCODE

No desenvolvimento web em equipe, boas práticas de documentação e versionamento são essenciais. O **GIT** é um sistema de controle de versões que gerencia diferentes versões e o histórico do código. O **GITHUB** é uma plataforma que usa GIT para hospedar e colaborar em projetos. O **VSCODE** é um editor de código que integra com GIT e GITHUB.

## GitHub

GitHub é uma plataforma para hospedagem e colaboração em projetos usando GIT, acessível globalmente para projetos privados e open source.

## Conceitos Fundamentais

- **Repositório**: Local onde o código é armazenado e monitorado.
- **Branch**: Cópia do código principal para trabalho paralelo, com a principal chamada "Master" ou "Main".
- **Merge**: Integra alterações de uma branch em outra, unificando o histórico do código. Conflitos devem ser resolvidos manualmente.

## README.md

README.md é um arquivo Markdown que fornece informações sobre o projeto.

## Criando Repositório no GitHub

1. No GitHub, vá para "Your repositories" e clique em "New".
2. Nomeie o repositório, defina a privacidade e adicione um README. Clique em "Create repository".

## Fork

"Fork" é copiar um repositório para sua conta no GitHub. Use para consultar ou contribuir com o código, clonando-o e criando uma branch.

## Clonando Repositórios

1. Copie a URL do repositório.
2. Execute `git clone url-do-repositorio` na linha de comando.

## Comandos Básicos do Git

- `git init`: Inicializa um repositório.
- `git add .`: Adiciona arquivos.
- `git commit -m "mensagem"`: Comita alterações.
- `git push origin master`: Envia alterações para o repositório remoto.
- `git checkout -b nome-da-branch`: Cria e muda para uma nova branch.
- `git pull origin master`: Atualiza a branch local com alterações do remoto.

## Subindo Repositório Existente

1. Crie um repositório no GitHub.
2. Na pasta do projeto, execute `git init`, `git add .`, `git commit -m "mensagem"`, `git remote add origin url-do-github`, e `git push origin master`.

## Contribuindo em Projetos Remotos

1. Clone o repositório: `git clone url-do-projeto`.
2. Atualize e crie uma branch: `git pull origin master`, `git checkout -b nome-da-sua-branch`.
3. Faça commit e envie alterações: `git add .`, `git commit -m "mensagem"`, `git push origin nome-da-sua-branch`.
4. Abra uma Pull Request para solicitar integração com a branch principal.

## Visual Studio

O **Visual Studio** é uma IDE da Microsoft para desenvolvimento de software com suporte a várias linguagens, depuração avançada e integração com GIT. Disponível em versões Community, Professional e Enterprise

## Visual Studio Code (VSCode)

O **Visual Studio Code (VSCode)** é um editor de código leve e extensível, ideal para desenvolvimento com suporte a GIT e várias extensões.
