# BuzzSearch
Encontre eventos, repositórios e tweets das tecnologias que você deseja seguir.

# Sobre
O projeto é dividido em duas partes: front-end e back-end. O primeiro, foi desenvolvido com Vanilla JS, HTML e CSS. Já o segundo utiliza Flask.

# Executando o Back-end
1. Instale o Python na sua máquina (sistemas UNIX-like já tem instalado a versão 2.7)
2. Instale o PIP
3. Instale as dependências que encontra-se no arquivo back/requirements.txt
```
pip install -r requirements.txt
```
4. Exporte as variáveis de ambiente
```
$ export FLASK_APP=back/run.py
$ export FLASK_DEBUG=1
```
5. Execute o servidor no terminal com o comando abaixo
```
$ flask run
```
6. Abra o arquivo index.html no browser
