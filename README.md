# Brincadeira

## Como brincar com esse repositório:

* Criar um fork

Ir pra página do fork e pegar a url para clonar

* Clonar:

```bash
	$ git clone url_fork
```

> Entrar na pasta do repositório

* Configurar o Upstream:

```bash
	$ git add remote upstream url_upstream
```

* Verificar origin e upstream

```bash
	$ git remote -v
```

* Editar os arquivos

```bash
	$ git status
	$ git add arquivo1 arquivo2
	$ git status
	$ git commit
	$ git status
```

> Repetir até ficar pronto

* Trazer mudanças do Upstream:

```bash
	$ git fetch upstream
	$ git rebase upstream/master
```

* Testar que tudo está funcionando certinho

* Enviar pro fork

```bash
	$ git push origin master
```

* Solicitar o Pull Request na página do fork

* Repetir o processo até o mundo acabar

