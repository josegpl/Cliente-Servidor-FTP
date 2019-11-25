# Cliente- Servidor FTP

Usando sockets em Python 3.7

Para executar o Servidor:

    python serv.py <numero da porta>
  
    
Cliente:

    python cli.py <URLservidor> <numero porta> (se executado localmente, então URLservidor = localhost)
    
Exemplo:

python serv.py 50000

-
python cli.py localhost 50000

Comandos

    'get <nome>' download arquivo do servidor

    'put <nome>' upload arquivo para servidor

    'ls' lista os arquivos no servidor

    'quit' desconecta


