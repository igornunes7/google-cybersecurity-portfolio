# Como publicar este portfólio no GitHub

## 1. Criar uma conta

Se ainda não tiver uma conta, acesse [github.com](https://github.com/), escolha **Sign up** e conclua o cadastro.

## 2. Criar o repositório

1. Entre no GitHub e clique no botão **+**, no canto superior direito.
2. Selecione **New repository**.
3. Em **Repository name**, use `google-cybersecurity-portfolio`.
4. Em **Description**, use: `My learning journey and practical portfolio for the Google Cybersecurity Professional Certificate.`
5. Selecione **Public**, se quiser usar o repositório como portfólio profissional.
6. Não marque as opções para criar README, `.gitignore` ou licença, pois estes arquivos locais serão enviados no primeiro commit.
7. Clique em **Create repository**.

## 3. Preparar os arquivos no computador

Abra um terminal dentro da pasta que contém este `README.md` e execute:

```bash
git init
git branch -M main
git add .
git commit -m "docs: create cybersecurity portfolio structure"
```

Se o Git pedir sua identidade, configure-a e repita o commit:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu-email-do-github@example.com"
```

Use no comando acima o e-mail associado à sua conta ou o endereço `noreply` fornecido pelo GitHub.

## 4. Conectar ao GitHub

Na página do repositório recém-criado, copie a URL HTTPS. Ela terá este formato:

```text
https://github.com/SEU-USUARIO/google-cybersecurity-portfolio.git
```

Execute, substituindo `SEU-USUARIO`:

```bash
git remote add origin https://github.com/SEU-USUARIO/google-cybersecurity-portfolio.git
git push -u origin main
```

O GitHub poderá abrir o navegador para autenticação. Nunca coloque senha ou token dentro de um arquivo do repositório.

## 5. Conferir a publicação

Atualize a página do repositório e confirme se aparecem:

- `README.md`;
- `GITHUB-SETUP.md`;
- a pasta `01-foundations-of-cybersecurity`;
- os quatro arquivos de anotações;
- a pasta `portfolio`.

## Próximos commits

Depois de personalizar o Professional Statement:

```bash
git add 01-foundations-of-cybersecurity/portfolio/professional-statement.md
git commit -m "docs: personalize professional statement"
git push
```

Ao concluir uma nova parte do portfólio, use mensagens curtas que descrevam a mudança, por exemplo:

```text
docs: add course 2 notes
feat: add network traffic analysis project
docs: update certificate progress
```

## Antes de cada envio

```bash
git status
git diff
```

Confira se não há senhas, tokens, e-mails privados, dados pessoais, respostas de avaliações ou conteúdo copiado do curso.
