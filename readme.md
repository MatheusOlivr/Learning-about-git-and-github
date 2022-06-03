## **INICIANDO O GIT E CRIANDO UM COMMIT**

### HOW TO CREATE A LOCAL REPOSITORY:

**You must use the command:**

```bash
git init
```

### HOW TO SEE HIDDEN FILE:

**You must use the command**

```bash
ls -a
```

### HOW TO CONFIGURE THE GIT:

**You must use the command**

```bash
/*For configure E-mail*/
	git config --global user.email "contato.matheusoliv@gmail.com"
/*For configure the author name*/
	git config --global user.name "yourname"
```

## **CICLO DE VIDA DOS ARQUIVOS NO GIT**

![https://imgur.com/oeA6yCtl.png](https://imgur.com/oeA6yCtl.png)

**Staged → These files be those that was not committed.**

**Unmodified → These files be those that was committed.**

**Modified → These files be those that was modify inside a commit, but still was not commited this modification.**

### HOW TO SEE WHAT FILES ARE NOT BE MONITORED BY GIT:

**You must use the command :**

```bash
git status
```

### HOW DO FOR THE FILES BE MONITORED BY GIT:

**You must use the command:**

```bash
/*for Monitored only one modified file*/
git add <filename>
/*for Monitored all file that was modified*/
git add -A 
```

### HOW TO SAVE ALL MODIFIEDS:

**You must use the command:**

```bash
git commit -m 'what was modified menssage'
```