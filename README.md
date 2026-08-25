# 3º Ano DS — Versionamento de Código e Mensageria

## Projeto colaborativo da turma

Este projeto foi desenvolvido para a disciplina de **Versionamento de Código e Mensageria**, do **3º Ano de Desenvolvimento de Sistemas** da **EE Dom João Nery**, com o professor **Yuri Batista de Brito**.

A proposta é simular um fluxo de colaboração utilizado em projetos reais de desenvolvimento de software. Cada grupo deverá contribuir para o projeto principal utilizando **Git e GitHub**, sem alterar diretamente o repositório oficial.

---

## Objetivo da atividade

Cada grupo deverá apresentar seu **projeto de TCC** dentro do site da turma.

Para isso, será utilizado o seguinte fluxo:

```text
Fork
  ↓
Clone
  ↓
Branch
  ↓
Alteração do projeto
  ↓
Commit
  ↓
Push
  ↓
Pull Request
  ↓
Code Review
  ↓
Merge
```

O objetivo não é apenas colocar as informações do TCC no site, mas também praticar um fluxo de versionamento e colaboração semelhante ao utilizado por equipes de desenvolvimento.

---

## Organização dos grupos

O projeto possui **7 grupos**.

Cada grupo possui:

```text
grupos/
├── grupo-01.html
├── grupo-02.html
├── grupo-03.html
├── grupo-04.html
├── grupo-05.html
├── grupo-06.html
└── grupo-07.html
```

Cada grupo deverá modificar **somente sua própria página**.

### Exemplo

Se você pertence ao Grupo 04, deverá trabalhar principalmente em:

```text
grupos/grupo-04.html
```

E no `index.html`, deverá alterar apenas o card correspondente ao Grupo 04.

---

## O que colocar no projeto

Cada grupo deverá apresentar seu TCC contendo, no mínimo:

* Nome do projeto;
* Integrantes;
* Descrição do projeto;
* Problema que o projeto pretende solucionar;
* Principais funcionalidades;
* Tecnologias utilizadas;
* Imagem ou identidade visual do projeto;
* Link para o projeto, caso já exista.

O conteúdo deve ser apresentado de forma **organizada, clara e profissional**.

---

# Regras importantes

### 1. Não altere o trabalho dos outros grupos

Se você é do Grupo 04, não altere:

```text
grupo-01.html
grupo-02.html
grupo-03.html
grupo-05.html
grupo-06.html
grupo-07.html
```

### 2. Não trabalhe diretamente na `main`

Cada grupo deverá criar sua própria branch.

Exemplo:

```bash
git switch -c grupo-04
```

### 3. Não faça alterações desnecessárias

Evite modificar arquivos que não fazem parte da sua tarefa.

### 4. Revise suas alterações antes do Push

Utilize:

```bash
git status
```

para verificar quais arquivos foram modificados.

---

# Estrutura do projeto

```text
3ds-versionamento-mensageria/
│
├── index.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── grupos/
│   ├── grupo-01.html
│   ├── grupo-02.html
│   ├── grupo-03.html
│   ├── grupo-04.html
│   ├── grupo-05.html
│   ├── grupo-06.html
│   └── grupo-07.html
│
└── README.md
```

---

# Fluxo que cada grupo deverá realizar

## 1. Fork

Faça um **Fork** deste repositório para sua conta do GitHub.

O Fork cria uma cópia do projeto para que seu grupo possa trabalhar sem modificar diretamente o projeto principal.

---

## 2. Clone

Clone o seu Fork para o computador:

```bash
git clone URL_DO_SEU_FORK
```

Entre na pasta:

```bash
cd 3ds-versionamento-mensageria
```

---

## 3. Crie uma Branch

Crie uma branch específica para o seu grupo.

Exemplo:

```bash
git switch -c grupo-04
```

Substitua `04` pelo número do seu grupo.

---

## 4. Faça as alterações

Abra o projeto no Visual Studio Code.

Modifique:

```text
index.html
```

e a página correspondente:

```text
grupos/grupo-XX.html
```

Adicione as informações do TCC do grupo.

---

## 5. Teste o site

Abra o `index.html` no navegador.

Confira:

* Seu card aparece corretamente;
* O card abre a página do seu grupo;
* As imagens aparecem;
* Os textos estão corretos;
* Os links funcionam;
* Os outros grupos continuam funcionando.

---

## 6. Confira as alterações

Execute:

```bash
git status
```

Verifique se os arquivos alterados são realmente os arquivos que você pretendia modificar.

---

## 7. Faça o Commit

Adicione as alterações:

```bash
git add .
```

Depois faça o commit:

```bash
git commit -m "Atualiza projeto do Grupo 04"
```

Troque `04` pelo número do seu grupo.

---

## 8. Faça o Push

Envie sua branch para o GitHub:

```bash
git push -u origin grupo-04
```

---

## 9. Crie a Pull Request

No GitHub, abra o seu Fork.

Depois crie uma **Pull Request** para o repositório principal do professor.

Título sugerido:

```text
Atualiza projeto do Grupo 04
```

Na descrição, explique brevemente o que foi realizado.

Exemplo:

```text
Neste Pull Request foram realizadas as seguintes alterações:

- Atualização do card do Grupo 04;
- Inclusão das informações do TCC;
- Atualização da página individual do grupo;
- Inclusão da imagem do projeto.
```

---

# Code Review

A Pull Request será analisada antes de entrar no projeto principal.

Durante a revisão poderão ser verificados:

* Organização do código;
* Funcionamento da página;
* Qualidade das informações;
* Links;
* Imagens;
* Alterações realizadas somente nos arquivos permitidos;
* Organização dos commits;
* Funcionamento do site.

Caso seja encontrada alguma alteração que precise ser corrigida, o grupo deverá realizar a correção e fazer um novo commit e Push.

---

# Checklist final

Antes de considerar a atividade concluída, verifique:

```text
[ ] Fiz o Fork do projeto
[ ] Clonei meu Fork
[ ] Criei uma Branch para meu grupo
[ ] Alterei somente meu card
[ ] Atualizei a página do meu grupo
[ ] Coloquei as informações do TCC
[ ] Testei o site
[ ] Executei git status
[ ] Fiz git add .
[ ] Fiz o commit
[ ] Fiz o Push
[ ] Criei a Pull Request
[ ] Conferi a Pull Request
```

---

## Professor

**Yuri Batista de Brito**

**Disciplina:** Versionamento de Código e Mensageria
**Curso:** Desenvolvimento de Sistemas — 3º Ano
**Escola:** EE Dom João Nery

> Este projeto é uma atividade prática de colaboração, versionamento e comunicação entre equipes de desenvolvimento.
