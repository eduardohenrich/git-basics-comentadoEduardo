# 06. Refatore nomes de arquivos

> Mude e remova os arquivos versionados.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)

---

## Comandos desta seção (3)

### 1. `git rm [arquivo]`

```bash
git rm [arquivo]
```

**O que faz:**

remove um arquivo do historico de monitoramento do Git e também o deleta da sua pasta física

**Quando usar / observação:**

quando se precisar apagar o arquivo do projeto definitivamente. Ou seja quando nao tem mais utilidade fazendo ele sumir tento do git quanto do computador.
---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**
Faz o git parar de monitorar o arquivo mas o matém intacto na pasta fisica computador

**Quando usar / observação:**

quando enviar arquivos sensíveis por engano por exemplo com senhas.

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

remomeia ou move para outra pasta o arquivo fisicamente no computador, 

**Quando usar / observação:**

Quando precisar renomear ou mover o arquivo de lugar.

---

## Checklist deste arquivo

- [x] 1. `git rm [arquivo]`
- [x] 2. `git rm --cached [arquivo]`
- [x] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
