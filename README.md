# Ebac-front-end

# Git
## Conceitos de Versionamento
- Histórico
- Quem alterou
- O que alterou
- Quando alterou
- Todos os arquivos
- Evolução contínua

Arquivo A  | Versão 1 | Versão 2
Arquivo B  | Versão 1 | Versão 2

## Instalação do Git

## Criar conta no GitHub

## Clonar projeto
- git clone https://github.com/LeandroLeance95/Curso-FrontEnd-Ebac.git

## Commits
informação de alteração
- após testado todo seu código
- git add *
- git commit -m "mensagem"
- git push
- git pull
## GitFlow
Fluxo do Git
 
### Branchs
São ramificações / versões paralelas

- main / master (vai para a produção, quando o projeto é publicado)
- develop (cópia da main, onde faço alterações na minha máquina local antes de publicar, testes, desenvolvimento, e commits)

- git checkout -b dev (comando para criar a branch developer, que é a ramificação da main, ou uma cópia)

- DOD = Definition of Done : critérios aceitos

- versionamento 1.2.10 (primeiro digito é quando já esta publicado na main, onde o código já está rodando, segundo digito é alterações importantes que foram feitas, terceito digito é apenas correções de bugs, pequenas alterações)