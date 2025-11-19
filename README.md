# 📁 Trabalho_angelo

Portfólio dos alunos de Design – Repositório oficial

Este repositório será utilizado para organização, criação e versionamento dos portfólios produzidos pelos alunos.
Siga as instruções abaixo para garantir que toda a equipe trabalhe de forma organizada e sem conflitos.

---

# 🚀 Primeira vez acessando o repositório?

## 1. Copie o link do repositório

No GitHub, clique no botão **"Code"** e copie o link HTTPS.

---

## 2. Abra o terminal no local onde deseja salvar o projeto

```bash
cd caminho/para/sua/pasta
```

---

## 3. Clone o repositório para sua máquina

```bash
git clone <link-do-repositorio>
```

Depois:

```bash
cd nome-do-repositorio
```

---

# 🔄 Já tenho o repositório clonado. E agora?

Se o projeto **já está na sua máquina**, siga estes passos sempre que for trabalhar:

---

## 1. Entre na pasta do repositório

```bash
cd caminho/para/o/repositorio
```

---

## 2. Verifique o status do repositório

```bash
git status
```

---

## 3. Atualize o repositório antes de trabalhar

```bash
git pull
```

---

# ✏️ Como enviar alterações para o repositório

Quando terminar de editar arquivos:

### 1. Confira alterações

```bash
git status
```

### 2. Adicione arquivos alterados

```bash
git add .
```

Ou selecione arquivos específicos:

```bash
git add caminho/arquivo.extensao
```

### 3. Faça um commit com uma mensagem clara

```bash
git commit -m "Descrição objetiva das alterações"
```

### 4. Envie para o repositório remoto

```bash
git push
```

---

# 🌿 Criando uma nova branch (boa prática recomendada)

Em vez de trabalhar direto na `main`:

```bash
git checkout -b nome-da-branch
```

Suba a branch para o GitHub:

```bash
git push -u origin nome-da-branch
```

---

# ⚠️ Resolvendo conflitos de merge (básico)

Caso apareça conflito ao rodar `git pull`:

1. Abra o arquivo com conflito
2. Procure trechos como:

```
<<<<<<< HEAD
(sua versão)
=======
(versão remota)
>>>>>>> main
```

3. Escolha qual versão manter ou combine as duas
4. Depois finalize:

```bash
git add .
git commit -m "Conflito resolvido"
git push
```

---

# 📌 Boas práticas da equipe

* Sempre fazer **git pull antes de começar**
* Criar branches para funcionalidades específicas
* Mensagens de commit devem ser claras e diretas
* Evitar subir arquivos pesados desnecessários
* Avisar a equipe ao alterar algo grande
