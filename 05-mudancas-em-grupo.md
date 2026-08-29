# 05. Mudanças em grupo

> Nomeie uma série de commits e combine os esforços completos.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)

---

## Comandos desta seção (5)

### 1. `git branch`

```bash
git branch
```

**O que faz:**

o comando git branch serve para criar, listar, renomear branches.

**Quando usar / observação:**

Sempre que precisar realizar alguma operação citada a cima.

---

### 2. `git branch [nome-do-branch]`

```bash
git branch [nome-do-branch]
```

**O que faz:**

Este comando cria uma nova ramificação a partir da atual que se esta. Sem mudar para ela de imediato.

**Quando usar / observação:**
Sempre que precisar criar uma nova branch.

---

### 3. `git switch -c [nome-do-branch]`

```bash
git switch -c [nome-do-branch]
```

**O que faz:**

cria uma nova branch e já muda para ela automaticamente.

**Quando usar / observação:**

Sempre que precisar criar e já se deslocar para ela.

---

### 4. `git merge [nome-do-branch]`

```bash
git merge [nome-do-branch]
```

**O que faz:**

une todas as alterações da outra branch para a atual.

**Quando usar / observação:**

Sempre que precisar unir alterações de uma branch à outra.

---

### 5. `git branch -d [nome-do-branch]`

```bash
git branch -d [nome-do-branch]
```

**O que faz:**

Deleta um branch local que já foi mesclado com a principal (feito merged)

**Quando usar / observação:**

quando quiser deletar uma branch com alterações já salvas na principal.

---

## Checklist deste arquivo

- [x] 1. `git branch`
- [x] 2. `git branch [nome-do-branch]`
- [x] 3. `git switch -c [nome-do-branch]`
- [x] 4. `git merge [nome-do-branch]`
- [x] 5. `git branch -d [nome-do-branch]`

---

[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)
