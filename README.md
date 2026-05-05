# Mural-3-DS-Juvenal

Bem-vindo ao nosso exercício prático de Git e GitHub! O objetivo desta atividade é simular um fluxo de trabalho real, utilizando **Forks**, **Branches** e **Pull Requests**.

O resultado final será um mural com o nome de todos os alunos que contribuíram para o projeto.

## Passo a Passo da Atividade

### 1. Fazer o Fork
No canto superior direito desta página, clique no botão **Fork**. Isto criará uma cópia exata deste repositório na sua conta pessoal do GitHub.

### 2. Clonar seu Repositório
Agora, no seu computador, abra o terminal dentro de uma pasta que você criou para essa atividade e clone o **seu** fork (substitua `seu-perfil` pelo seu nome no GitHub):
```bash
git clone https://github.com/seu-perfil/Mural-3-DS-Juvenal.git
```

### 3. Criar uma Nova Branch

Entre na pasta do projeto e crie uma branch exclusiva para a sua alteração:
```bash
cd Mural-3-DS-Juvenal

git switch -c add-nome-do-aluno
```

### 4. Editar o Arquivo

Abra o arquivo alunos.md num editor de texto (VS Code, Notepad, etc.) e adicione seu nome e uma curiosidade ou uma tecnologia que você gosta de estudar.
Exemplo: - Talita - Amo viajar

## 5. Guardar e Enviar as Alterações

No terminal, prepare o arquivo e faça o commit:
```bash
git add alunos.md

git commit -m "feat: adicionar nome-aluno à lista de alunos"

git push origin nome-da-sua-branch
```

## 6. Abrir o Pull Request (PR)

Volte à página do seu fork no GitHub. Você verá um aviso amarelo escrito "Compare & pull request".

- Clique nesse botão.
- Escreva uma breve descrição da sua alteração.
- Clique em "Create pull request".

## ✅ O que acontece agora?

O "dono" do projeto original (a professora) receberá uma notificação, irá rever o seu código e, se estiver tudo correto, fará o Merge. 

Parabéns! A sua contribuição fará parte do projeto oficial.

Dúvidas? Levante a mão ou consulte o colega do lado! Vamos programar!
