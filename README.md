# Python Avançado: Estendendo C para Python  -  Parte I

Tutorial: um binding de C para Python de uma simples calculadora
Você pode acessar o link do tutorial no Medium [clicando aqui](https://medium.com/@diegocatalao/python-avan%C3%A7ado-estendendo-c-para-python-parte-i-a3da91a69cb4).

## Descrição

Este repositório é para a primeira parte do Tutorial Avançado de Python. Para este tutorial é proposto a inicialização e criação de módulos Python em C. Destina-se a entusiastas e programadores que buscam melhor compreenção de como fazer a portabilidade de suas funções escritas em C para Python ou libs que só foram implementadas em C.

## Dependências

Para este projeto é requerido a versão do Python >= 3.8 e algumas dependências de desenvolvimento:

```bash
# entendendo que você deve usar Ubuntu
$ sudo apt-get install python3.8
$ sudo apt-get install python3.8-dev
```

## Instalação

Para instalar o módulo você deve usar o `setup.py` que já está configurado para tal:

```bash
$ python3.8 setup.py build
$ python3.8 setup.py install
```

## Testando a aplicação

Você pode testar a aplicação criando um arquivo que irá chamar as funções escritas em CPython ou executar os testes unitáris na pasta `tests/`.

```bash
$ python3.8 -m unittest
```

## Autores

- Diego H S Catalão: [LinkedIn](https://www.linkedin.com/in/diego-catal%C3%A3o-573110207/) | [GitHub](https://github.com/diegocatalao)

## Licença

Este projeto está licenciado com a licença do MIT.