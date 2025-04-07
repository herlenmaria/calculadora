# Calculadora

Este repositório contém um código em Python uma calculadora simples que realiza operações básicas de **adição, subtração, multiplicação e divisão** e um arquivo shell script (calculadora.sh) para facilitar a execução do código Python

---

## Como executar


1. Clonar o Repositório
Primeiro, clone este repositório para o seu computador:

https://github.com/herlenmaria/calculadora.git

2. Navegar até o Diretório 
Depois de clonar, entre no diretório onde o repositório foi salvo:

```bash
cd caminho/para/seu/repositório
```


3. Criar e Editar o Arquivo calculadora.sh
Crie o arquivo shell script com o seguinte comando:

nano calculadora.sh

Isso abrirá o editor de texto nano. Dentro do arquivo, cole o seguinte código:

```bash
#!/bin/bash
#Script para executar a calculadora Python
python3 calculadora.py
```


4. Tornar o Script Executável
Você precisará alterar as permissões. Execute o seguinte comando:

```bash
chmod +x calculadora.sh
```

Isso garante que você pode executar o arquivo como um script.

5. Definir Permissões de Acesso
Para garantir que apenas o proprietário do arquivo tenha permissão de escrita e outros usuários tenham apenas permissão de leitura, use:

```bash
chmod 744 calculadora.sh
```

6. Executar o Script
Agora, você pode rodar o script para executar a calculadora Python com o seguinte comando:
```bash
./calculadora.sh
```


Requisitos
Python 3.10 ou superior

Terminal (Linux/Mac) ou Git Bash (no Windows)

Observação
Certifique-se de que o Python 3 esteja instalado na sua máquina. Se não estiver, você pode instalá-lo com:
```bash
sudo apt-get install python3
```

👩‍💻 Autor
Herlen Maria



