
# Sumário

Guilherme Vaz, DCC/FCUP

Aplicação Python demonstrando o acesso à BD

#  Referência

- [PyMySQL](https://pymysql.readthedocs.io/)
- [Flask](https://flask.palletsprojects.com/en/2.0.x/)
- [Jinja templates](https://jinja.palletsprojects.com/en/3.0.x/)


# Instalação de dependências

## Python 3 e pip 

Deve ter o Python 3 e o gestor de pacotes pip instalado. Pode
instalar os mesmos em Ubuntu por exemplo usando:

```
sudo apt-get install python3 python3-pip
```

## Bibliotecas Python

```
pip3 install --user Flask==1.1.4 PyMySQL==1.0.2 cryptography==36.0.0
```


# Configuração da BD

Edite o ficheiro `db.py` no que se refere à configuração da sua BD, modificando os parâmetros `DB` (nome da base de dados), `USER` (nome do utilizador) e `PASSWORD` (senha do utilizador).

Teste o acesso executando:

```
python3 test_db_connection.py NOME_DE_UMA_TABELA
```



# Execução

Inicie a aplicação executando `python3 server.py` e interaja com a mesma
abrindo uma janela no seu browser  com o endereço [__http://localhost:9001/__](http://localhost:9001/) 

```

```



