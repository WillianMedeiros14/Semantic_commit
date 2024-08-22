<h1 align="center">

 <img alt=" Commit Semântico" title=" Commit Semântico" src="https://git-scm.com/images/logo@2x.png" width="250px" />
 <br>
 Commit Semântico
</h1>

## 💻 Definição

O objetivo do Commit Semântico no desenvolvimento de software é atribuir significado aos commits realizados dutante o processo de desenvolvimento.<br>
A medida que o projeto cresce, mais regras e arquivos são implementadas e diferentes pessoas podem passar por ele.
Assim, os commits devem fazer sentido a cada alteração do código, tornando assim uma melhor compreensão e organização, para que você compreenda doque se trata aquela alteração observando a mensagem do commit.
<br>

## ⓘ Como utilizar?

- A mensagem deve seguir a estrutura abaixo:

```bash
<tipo>(escopo opcional): <descrição>
```

- O escopo é uma parte opcional que especifica a área do código que está sendo afetada. Ele é especialmente útil em projetos grandes, onde muitas funcionalidades estão em desenvolvimento simultaneamente.

## ⓘ Tipos

```bash
feat: Introdução de uma nova funcionalidade.
```

```bash
fix: Correção de um bug.
```

```bash
chore: Alterações que não impactam o código ou os testes (ex.: atualizações de dependências).
```

```bash
docs: Mudanças na documentação.
```

```bash
style: Alterações de formatação, semântica, ou layout (ex.: remoção de espaços em branco).
```

```bash
refactor: Mudanças no código que não corrigem bugs ou adicionam funcionalidades.
```

```bash
test: Adição ou modificação de testes.
```

```bash
perf: Alterações de código que melhoram o desempenho.
```

```bash
build: Mudanças que afetam o sistema de build ou dependências externas (ex.: ferramentas de compilação).
```

```bash
ci: Mudanças em arquivos de configuração e scripts de CI (Continuous Integration).
```

## Exemplos

- Sem escopo:

```bash
git commit -m "refactor: simplificar lógica de autenticação"
```

- Com escopo:

```bash
git commit -m "feat(login): adicionar validação de email"
```

```bash
git commit -m "docs(readme): atualizar instruções de configuração do projeto"
```

## gitignore no C#/dotnet

Assim como para outros projetos e tecnologias, o .gitignore serve para subir parao s repositórios apenas os arquivos obrigatórios e necessários.

- Para criar o arquivo .gitignore execute o comando abaixo:

```bash
dotnet new gitignore
```

## 🚀 Principais comandos git

```bash
git remote add <nome> <url>: adicionar um repositório remoto.

#Exemplo:
git remote add origin https://github.com/usuario/repositorio.git
```

```bash
git remote remove <nome>: remover remover um repositório remoto

#Exemplo:
git remote remove origin
```

```bash
git remote set-url <nome> <nova-url>: Alterar um repositório remoto

#Exemplo:
git remote set-url origin https://github.com/usuario/novo-repositorio.git
```

```bash
git init: Inicializa um novo repositório Git em um diretório.
```

```bash
git clone <url>: Cria uma cópia local de um repositório remoto.
```

```bash
git add <arquivo>: Adiciona arquivos ao índice para o próximo commit.
```

```bash
git add . :para adicionar todos os arquivos modificados.
```

```bash
git commit -m "<mensagem>": Cria um novo commit com as mudanças adicionadas, associadas a uma mensagem descritiva.
```

```bash
git commit --amend -m "<mensagem>": Altera a mensagem do último commit realizado.
```

```bash
git status: Mostra o status dos arquivos no repositório, incluindo quais arquivos foram modificados, adicionados ou removidos.
```

```bash
git pull: Baixa e integra mudanças do repositório remoto para o sua branch atual.
```

```bash
git push: Envia seus commits locais para o repositório remoto.
```

```bash
git branch: Lista todos as branches no repositório.
```

```bash
git branch <nome-da-branch>: criar uma nova branch.
```

```bash
git checkout <branch>: Altera para a branch especificado.
```

```bash
git checkout -b <nome-do-branch>: cria e muda automaticamente para uma nova branch.
```

```bash
git merge <branch>: Mescla a branch especificado com o branch atual.
```

```bash
git log: Exibe o histórico de commits.
```

```bash
git diff: Mostra as diferenças entre o estado atual e o último commit.
```

```bash
git reset --soft HEAD~1: desfazer o último commit e deixar as mudanças como "não commitadas" no seu diretório de trabalho.
```

```bash
git reset --hard HEAD~1: desfazer o último commit e remover todas as alterações associadas.
```

```bash
git revert <commit>: Cria um novo commit que desfaz as mudanças do commit especificado.
```

## 🚀 Fontes ultilizadas

- **[Guia Completo para Transformar Seus Commits em Histórias: O Poder do Commit Semântico no GitHub](https://medium.com/@aluiza.primo/guia-completo-para-transformar-seus-commits-em-hist%C3%B3rias-o-poder-do-commit-sem%C3%A2ntico-no-github-aa074992cc3b)**.

- **[Padrões de Commits (Commit Patterns)](https://dev.to/renatoadorno/padroes-de-commits-commit-patterns-41co)**.

- **[Referência Git)](https://git-scm.com/docs)**.
