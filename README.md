# Instalação e Configuração do Ambiente

* Editores de texto
  * [Atom](https://atom.io/)
  * [Sublime Text](https://www.sublimetext.com/)
* [Git](https://git-scm.com/download/)

# Temas

* [Linha de Comando](http://swcarpentry.github.io/shell-novice/)
* [Controle de Versão](http://swcarpentry.github.io/git-novice/)
* [Análise de Dados com R](https://swcarpentry.github.io/r-novice-gapminder/)

# Comandos

* Configurar usuário e editor de texto
  ```bash
  git config --global user.name "Francisco Junior"
  git config --global user.email "francisco.junior@cge.mg.gov.br"
  git config --global core.editor "atom --wait"
  git config --list # lista as configuracoes atuais
  ```

* Inicializar repositório
  ```bash
  git init
  ```

* Fluxo de trabalho

  ```bash
  git add <files>
  git commit -m "<message>"
  ```

* Utilitários

  ```bash
  git status # estado do repositório
  git diff # alteracoes nos arquivos
  git log
  ```

* Sincronização alterações

  ```bash
  git clone <url>
  ```

# Atalhos

## Git Bash

* 2*tab

    Autocompletar

* `ctrl + l`

    Subir/Limpar tela

* Colar

    ```
    shift + insert
    ```


## Atom

* `ctrl+shift+p`

    Paleta de comandos

* `ctrl+shift+m`

    Preview de arquivo markdown

## Git

* `shift` botão direito

      Abrir git bash


# Licões Aprendidas

* Mostrar exemplo motivante no inicio
  * Eg. Renomear arquivos

* Como utilizar `git mv` corretamente?

# Status

* Como configurar editor de texto do git
