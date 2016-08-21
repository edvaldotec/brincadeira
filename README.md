# Brincadeira

## Como brincar com esse repositório:

* Criar um fork

Ir pra página do fork e pegar a url para clonar

* Clonar:

```bash
	$ git clone url_fork
```

Entrar na pasta do repositório

Editar os arquivos

```bash
	$ git status
	$ git add arquivo1 arquivo2
	$ git status
	$ git commit
	$ git status
```

Repetir até ficar pronto

* Configurar o Upstream:

```bash
	$ git add remote upstream url_upstream
```

* Trazer mudanças do Upstream:

```bash
	$ git fetch upstream
	$ git rebase upstream/master
```

* Enviar pro fork

```bash
	$ git push origin master
```
