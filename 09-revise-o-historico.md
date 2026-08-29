# 09. Revise o histórico

> Navegue e inspecione a evolução dos arquivos do projeto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)

---

## Comandos desta seção (4)

### 1. `git log`

```bash
git log
```

**O que faz:**

o comando git log serve para visualizar o historico de commits de um repositório.

**Quando usar / observação:**

sempre que precisar usar para ver os commits realizados ao longo do tempo.

---

### 2. `git log --follow [arquivo]`

```bash
git log --follow [arquivo]
```

**O que faz:**

Serve para ver o histórico completo de um arquivo específico, mesmo renomeado ou movido de pasta.

**Quando usar / observação:**

quando precisa investigar um arquivo para ver a origem de um bug antigo.

---

### 3. `git diff [primeiro-branch]...[segundo-branch]`

```bash
git diff [primeiro-branch]...[segundo-branch]
```

**O que faz:**

Ele mostra apenas as alterações que foram feitas no branchB desde o momento em que ele se separou do branchA.

**Quando usar / observação:**

usado antes de enviar o codigo para aprovação, para ter certeza quando se esta adicionando elementos novos.

---

### 4. `git show [commit]`

```bash
git show [commit]
```

**O que faz:**

serve para ver os detalhes especificos e completos de um commit específico.

**Quando usar / observação:**

usado para revisar o trabalho feito antes de dar push. Ou quando precisa ver o conteúdo que mudou dentro dele.

---

## Checklist deste arquivo

- [x] 1. `git log`
- [x] 2. `git log --follow [arquivo]`
- [x] 3. `git diff [primeiro-branch]...[segundo-branch]`
- [x] 4. `git show [commit]`

---

[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)
