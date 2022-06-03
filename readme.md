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
**For configure E-mail**
```bash
	git config --global user.email "youremail"
```
**For configure the author name**
```bash
	git config --global user.name "yourname"
```

## **CICLO DE VIDA DOS ARQUIVOS NO GIT**

![https://imgur.com/oeA6yCtl.png](https://imgur.com/oeA6yCtl.png)

* **Staged → These files be those that was not committed.**

* **Unmodified → These files be those that was committed.**

* **Modified → These files be those that was modify inside a commit, but still was not commited this modification.**

### HOW TO SEE WHAT FILES ARE NOT BE MONITORED BY GIT:

**You must use the command :**

```bash
git status
```

### HOW DO FOR THE FILES BE MONITORED BY GIT:

**You must use the command:**


**For Monitored only one modified file**
```bash
git add <filename>
```

**For Monitored all file that was modified**
```bash
git add -A 
```

### HOW TO SAVE ALL MODIFIEDS:

**You must use the command:**

```bash
git commit -m 'what was modified menssage'
```