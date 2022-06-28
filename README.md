Instalação do NodeJs no Linux Ubuntu 20.04
===

Utilizaremos o mvn para instalação do Node e NPM. NVM é um gerenciador de versão node.js, que trabalha com qualquer shel POSIX-compilant, em particular nas plataformas: unix, macOS e Windows WSL.

---
<H2> Instalação NVM </H2>

Para instalação de outras versões ou em outro SO basta seguir o Link do [projeto](https://github.com/nvm-sh/nvm)

`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`

Para verificar que o nvm está instalado, digite `nvm --version`. Se você obtiver um número como **0.39.1**, saberá que o nvm foi instalado com sucesso.

---
<h2>Instalação NodeJS</h2>

Agora, vamos instalar o **Nodejs versão 16.15.1**.

Basta executar o comando `nvm install 16.15.1`.

Você pode usar um comando semelhante para instalar qualquer versão do node que quiser, usando o comando `nvm install <versão-desejada>`.

Este comando instala automaticamente o nodejs, bem como a versão mais recente do **npm**.

Se você já precisou trocar as versões do node, basta executar `nvm use <numero-da-versao>` , para utilizar a **versão 16.13.2** por exemplo, o comando seria: `nvm use v16.13.2`.

Para listar as versões diferentes do node que você tem instaladas com o nvm, basta rodar o comando: `nvm ls`.

---
<h3>Comandos Node</h3>

`node --version` - verifica a versão node instalada

`npm --version` - verifica a versão npm instalada

`node arquivo.js` - Executa o aruivo.js no terminal