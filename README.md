# 🐍 Python POO (Programação Orientada a Objetos)
Este repositório é dedicado aos meus estudos de orientação a objetos em Python.

## 🤖 Tecnologias Utilizadas
- Python
- PyCharm

## 📊 Funcionalidades do Projeto
O projeto contém exemplos de classes e métodos em Python para demonstrar os conceitos de Programação Orientada a Objetos. Atualmente, o repositório contém exemplos de:
- Contas bancárias com verificação de limite
- Manipulação de datas

## 📁 Estrutura do Repositório
- `conta.py`: Contém a classe e métodos relacionados as contas bancárias.
- `datas.py`: Contém a classe e métodos relacionados a manipulação de datas.

## 🛠️ Como Rodar o Projeto
Para rodar os exemplos, siga os passos abaixo:

1. Clone este repositório:
    ```bash
    # Clonando o repositório
    git clone https://github.com/johnlaff/python-poo.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    # Entrando no diretório
    cd python-poo
    ```
3. Abra um terminal Python (como o console Python do PyCharm) e importe as classes desejadas:
    ```python
    # Importando a classe Conta
    from conta import Conta
    ```
4. Crie uma nova conta:
    ```python
    # Criando uma nova conta
    conta = Conta(123, "João", 500, 1000)
    ```

### Exemplo de Uso no Console Python
```python
# Importando a classe Conta
from conta import Conta

# Criando um objeto da classe Conta
conta = Conta(123, "João", 500, 1000)

# Verificando o saldo e o limite
conta.saldo
conta.limite

# Tentando sacar um valor maior que o limite
conta.saca(1600)

```

## 📚 Mais Informações
Este projeto faz parte do meu aprendizado em Python e Programação Orientada a Objetos.
