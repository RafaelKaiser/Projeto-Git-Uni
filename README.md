# 🚀 Projeto Colaborativo – Perfis da Turma

Este é um projeto colaborativo criado para aprendermos na prática como funciona o **Git**, **GitHub** e o trabalho em equipe no desenvolvimento de software.

Cada aluno vai criar uma página de perfil (estilo currículo) e adicioná-la ao site da turma, que ficará publicado na internet usando o **GitHub Pages**.

---

## ✅ Passo a Passo – Contribuindo no Projeto no GitHub + Publicando no GitHub Pages

---

### 1️⃣ Criando sua Conta no GitHub

1. Acesse [https://github.com](https://github.com)
2. Clique em **Sign Up** (Cadastrar-se).
3. Crie seu nome de usuário, email e senha.
4. Confirme seu cadastro no email.

---

### 2️⃣ Fazendo Fork do Projeto

> **Fork** significa criar uma cópia deste projeto no seu próprio GitHub para que você possa editar e colaborar.

1. Acesse o repositório principal do projeto (enviado pelo professor).
2. No canto superior direito, clique no botão **“Fork”**.
3. Aguarde. Agora você tem uma cópia deste projeto no seu próprio GitHub.

---

### 3️⃣ Clonando o Repositório para seu Computador

1. No seu repositório (o fork que você acabou de criar):
   - Clique no botão **“Code”** (cor verde).
   - Copie o link que aparece (começa com `https://`).

2. Abra o terminal (Git Bash, CMD, PowerShell ou terminal do VS Code).

3. Navegue até a pasta onde deseja salvar:
```bash
cd Documentos
```

4. Execute o comando para clonar:
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

---

### 4️⃣ Criando sua Página de Perfil

1. Acesse a pasta do projeto:
```bash
cd seu-repositorio
```

2. Copie o arquivo `template.html` e crie um novo arquivo com seu nome:
```bash
cp template.html seu-nome.html
```
> No Windows, se o `cp` não funcionar, use:
```bash
copy template.html seu-nome.html
```

3. Abra o projeto no VS Code:
```bash
code .
```

4. Edite o arquivo `seu-nome.html`:
   - Preencha com suas informações pessoais, como nome, sobre você, habilidades e contato.

5. No arquivo `index.html`, adicione seu nome no menu:
```html
<li><a href="seu-nome.html">Seu Nome</a></li>
```

---

### 5️⃣ Salvando e Enviando para o GitHub (Commit + Push)

1. Veja os arquivos alterados:
```bash
git status
```

2. Adicione os arquivos para serem preparados para envio:
```bash
git add .
```

3. Crie um commit com uma mensagem:
```bash
git commit -m "Adicionando meu perfil"
```

4. Envie os arquivos para seu repositório no GitHub:
```bash
git push origin main
```
> ⚠️ Se o nome do seu branch for `master`, substitua `main` por `master`.

---

### 6️⃣ (Opcional) Criando um Pull Request para o Repositório do Professor

> Se o professor permitir, você pode enviar suas alterações para o projeto principal.

1. No seu repositório no GitHub, clique em **“Pull Request”**.
2. Clique em **“New Pull Request”**.
3. Confira se está correto:
   - **base repository** → projeto do professor.
   - **head repository** → seu repositório.
4. Adicione um título (ex.: `Adicionando perfil Seu Nome`).
5. Clique em **“Create Pull Request”**.



## 💡 Dicas Importantes

- Antes de começar a trabalhar, sempre execute:
```bash
git pull origin main
```
> Isso garante que você está trabalhando na versão mais atualizada.

- Atenção ao editar o arquivo `index.html`: não apague os nomes dos colegas, apenas adicione o seu.

- Se acontecerem conflitos, é uma ótima oportunidade para aprendermos juntos como resolvê-los!

---

👍 Bom trabalho e divirta-se aprendendo Git, GitHub e colaboração! 🚀😎
