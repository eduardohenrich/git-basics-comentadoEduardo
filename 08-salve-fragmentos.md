# 08. Salve fragmentos

> Arquive e restaure mudanças incompletas.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)

---

## Comandos desta seção (4)

### 1. `git stash`

```bash
git stash
```

**O que faz:**

guarda temporariamente as alterações feitas e que não foram finalizadas para limpar o diretório de trabalho, sem precisar fazer um commit incompleto.

**Quando usar / observação:**
Sempre que não terminar uma alteração por completo, para não fazer um commit incompleto.

---

### 2. `git stash pop`

```bash
git stash pop
```

**O que faz:**

Ele serve para retornar "recuperar" exatamente de onde parou antes de ter guardado o seu trabalho com o git stash.

**Quando usar / observação:**

deve usar o git stash pop quando terminou a interrupção e quer voltar a trabalhar no seu código inacabado.

---

### 3. `git stash list`

```bash
git stash list
```

**O que faz:**

O comando git stash list mostra a lista de todos os rascunhos que foram guardados na "gaveta" do Git.

**Quando usar / observação:**

quando se tem múltiplos stashes acumulados, e se precisar saber qual rasculho quer resgatar.
---

### 4. `git stash drop`

```bash
git stash drop
```

**O que faz:**

deleta permanentemente um rascunho da "gaveta" de stashes 

**Quando usar / observação:**

por exemplo quando o racunho guardado não é mais necessário.
---

## Checklist deste arquivo

- [x] 1. `git stash`
- [x] 2. `git stash pop`
- [x] 3. `git stash list`
- [x] 4. `git stash drop`

---

[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)
