<br>
<div align="center">

  ## Jogo da velha em python usando sockets.

</div>

<br>

---
## Sobre
Na disciplina de Redes de Computadores, o trabalho final consistiu na criação de uma aplicação multiplayer por meio do uso de sockets. A aplicação desenvolvida foi um jogo da velha.

## Instruções de Uso
Para executar este projeto, você precisará ter o [Python](https://www.python.org/downloads/) instalado. Com isso, você pode clonar este repositório e instalar as dependências.
```sh
  # Clone este repositório
  git clone https://github.com/marianasciment0/JogodaVelha
```
Após clonar o repositório, você precisará instalar as dependências. Para fazer isso, execute os seguintes comandos:
```sh
  # Criando um ambiente virtual
  python3 -m venv env # ou python -m venv env, dependendo do seu sistema operacional
  # Ativando o ambiente virtual
  . env/bin/activate # ou env/Scripts/activate, dependendo do seu sistema operacional
  # Instalando as dependências
  pip install -r requirements.txt
```
Com as dependências instaladas, você precisará iniciar o servidor de soquete. Para fazer isso, execute o seguinte comando:
```sh
  # Iniciando o servidor de soquete
  python server.py # lembre-se de ter o ambiente virtual ativado
```
Por padrão, o servidor estará rodando na porta 5000. Se você quiser mudar isso, você pode fazer isso alterando o arquivo `server.py`. Depois de iniciar o servidor, você pode iniciar a GUI. Para fazer isso, execute o seguinte comando:
```sh
  # Iniciando GUI
  python main.py # lembre-se de ter o ambiente virtual ativado
```
Agora seu cliente está concorrendo! Seu oponente pode fazer o mesmo em sua máquina na mesma rede e vocês podem jogar juntos! (ou você pode abrir dois terminais e executar o cliente duas vezes)