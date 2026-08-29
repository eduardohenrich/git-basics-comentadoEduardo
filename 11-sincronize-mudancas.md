# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

O comando git fetch baixa os commits, arquivos, tags e referências do repositório remoto para o seu repositório local, mas sem aplicar nenhuma alteração no código de trabalho atual.

**Quando usar / observação:**

usar o git fetch sempre que quiser saber o que mudou no servidor, mas sem o risco de quebrar ou alterar o código que esta escrevendo agora.

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

une as alterações de uma branch remota específica (como origin/main) diretamente na branch local em que está no momento.

**Quando usar / observação:**

sempre que quiser trazer as novidades do servidor para o codigo local após ter rodado o git fetch

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

envia os commits locais da branch especificada para o repositório remoto colocando um apelido (alias).

**Quando usar / observação:**

sempre que quiser compartilhar o trabalho com a equipe ou salvar uma cópia de segurança do codigo na nuvem.

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

baixa todos as atualizações do repositorio remoto de commits que ainda não se possui localmente para a máquina.

**Quando usar / observação:**

sempre que quiser atualizar a branch local com as atualizações de outros desenvolvedores.

---

## Checklist deste arquivo

- [x] 1. `git fetch [nome-remoto]`
- [x] 2. `git merge [nome-remoto]/[branch]`
- [x] 3. `git push [alias] [branch]`
- [x] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
