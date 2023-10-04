<br>
<div align="center">
  # Jogo da velha em python usando sockets.
</div>

<br>

---
## Sobre
Na disciplina de Redes de Computadores, o trabalho final consistiu na criação de uma aplicação multiplayer por meio do uso de sockets. A aplicação desenvolvida foi um jogo da velha.

## Instructions for Use
Para executar este projeto, você precisará ter o [Python](https://www.python.org/downloads/) instalado. Com isso, você pode clonar este repositório e instalar as dependências.
```sh
  # Clone this repository
  git clone https://github.com/marianasciment0/JogodaVelha
```
Após clonar o repositório, você precisará instalar as dependências. Para fazer isso, execute os seguintes comandos:
```sh
  # Creating a virtual environment
  python3 -m venv env # or python -m venv env, depending on your operating system
  # Activating the virtual environment
  . env/bin/activate # or env/Scripts/activate, depending on your operating system
  # Installing the dependencies
  pip install -r requirements.txt
```
Com as dependências instaladas, você precisará iniciar o servidor de soquete. Para fazer isso, execute o seguinte comando:
```sh
  # Starting the socket server
  python server.py # remember to have the virtual environment activated
```
Por padrão, o servidor estará rodando na porta 5000. Se você quiser mudar isso, você pode fazer isso alterando o arquivo `server.py`. Depois de iniciar o servidor, você pode iniciar a GUI. Para fazer isso, execute o seguinte comando:
```sh
  # Starting the GUI
  python main.py # remember to have the virtual environment activated
```

`Agora seu cliente está concorrendo! Seu oponente pode fazer o mesmo em sua máquina na mesma rede e vocês podem jogar juntos! (ou você pode abrir dois terminais e executar o cliente duas vezes)`