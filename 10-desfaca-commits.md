# 10. Desfaça commits

> Apague enganos e crie um histórico substituto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)

---

## Comandos desta seção (2)

### 1. `git reset [commit]`

```bash
git reset [commit]
```

**O que faz:**

O comando git reset commit serve para mover o branch atual de volta para um commit específico do passado, alterando o histórico do seu projeto.

**Quando usar / observação:**

para corrigir um erro recente, quando se faz um commit que causou algum bug e precisa volta para trás para resolver.

---

### 2. `git reset --hard [commit]`

```bash
git reset --hard [commit]
```

**O que faz:**

força a branch atual a voltar exatamente ao estado daquele commit específico, destruindo permanentemente qualquer alteração feita depois dele.

**Quando usar / observação:**

para descartar um experimento que deu errado por exemplo.

---

## Checklist deste arquivo

- [x] 1. `git reset [commit]`
- [x] 2. `git reset --hard [commit]`

---

[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)
