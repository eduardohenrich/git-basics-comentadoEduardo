# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**
 
O git status é um comando para mostrar onde você está. No caso em qual branch se esta atualmente e os arquivos que foram modificados.

**Quando usar / observação:**
Sempre que precisar ter certeza ou precisar saber a branch que esta ou qual arquivo foi modificado.
---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

Este comando mostra o que foi modificado dentro de um arquivo, ou seja ele mostra o antes e depois de uma alteração.

**Quando usar / observação:**

Quando precisa saber sobre alguma alteração.

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

Adiciona os arquivos modificados para o staging onde ficam preparados para serem comitados posteriormente.

**Quando usar / observação:**

Sempre que terminar alguma alteração em algum arquivo.

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

Serve para mostrar as diferenças entre os arquivos que já foram preparados com git add com o ultimo commit.

**Quando usar / observação:**
Logo antes de executar algum commit para ver extamante onde foram feitas alterações;.
<!-- TODO: opcional, mas conta ponto. -->

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

Este comando remove arquivos da area de preparação, staging.

**Quando usar / observação:**

Sempre que precisar remover algum arquivo da area de preparação.

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

Faz um commit ou seja escreve uma alteração na "linha do tempo" do histórico de algum projeto.

**Quando usar / observação:**
Sempre que fizer algum ajuste ou atualização de algum projeto.

---

## Checklist deste arquivo

- [x] 1. `git status`
- [x] 2. `git diff`
- [x] 3. `git add [arquivo]`
- [x] 4. `git diff --staged`
- [x] 5. `git reset [arquivo]`
- [x] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
