# Minha API

Projeto de MVP para a conclusão do Sprint I da Pós Graduação em Engenharia de Software pela PUC-RIO

O Software desenvolvido nesse projeto tem como finalidade cadastrar os Bois de uma fazenda, bem como suas pesagens para
o acompanhamento do processo de engorda.

Requisitos adicionais da API adicionados pelo autor:
1) Banco de dados deve conter duas tabelas: Boi e Peso;
2) Tabela de Boi deve adicionar apenas um boi por brinco de cadastro;
3) Tabela peso, deve aceitar apenas entradas de peso para brincos com boi cadastrado;

---
## Como executar 


Será necessário ter todas as libs python listadas no `requirements.txt` instaladas.
Após clonar o repositório, é necessário ir ao diretório raiz, pelo terminal, para poder executar os comandos descritos abaixo.

> É fortemente indicado o uso de ambientes virtuais do tipo [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html).

```
(env)$ pip install -r requirements.txt
```

Este comando instala as dependências/bibliotecas, descritas no arquivo `requirements.txt`.

Para executar a API  basta executar:

```
(env)$ flask run --host 0.0.0.0 --port 5000
```

Em modo de desenvolvimento é recomendado executar utilizando o parâmetro reload, que reiniciará o servidor
automaticamente após uma mudança no código fonte. 

```
(env)$ flask run --host 0.0.0.0 --port 5000 --reload
```

Abra o [http://localhost:5000/#/](http://localhost:5000/#/) no navegador para verificar o status da API em execução.
