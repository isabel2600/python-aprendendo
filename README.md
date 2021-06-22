# python-aprendendo
Aprendendo sobre python

![Amazon_AWS-232F3E_style=for-the-badge logo=amazon-aws logoColor=white](https://user-images.githubusercontent.com/68034656/122946320-a63fac80-d34f-11eb-9064-01441ec41c23.png)

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) 
 ### Resumo de texto usando Cleaner.robos.kroton



  <br /> Projeto que serve de referência para o projeto robos.Kroton.

Ou seja, é um projeto proposto para ser clonado e pode ser reutilizado no desenvolvimento dos futuros projetos da 1sti.

Este projeto inclui um conjunto "completo" de ferramentas, já configuradas, para o desenvolvimentode filtros de ec2 na aws.

O projeto inclui:
 
 1. config.yaml = consiste em um arquivo yaml que possui todas as variáveis que serão usadas como filtros, dentro da nossa receita principal em python:
- Como configurar o yaml.
- Todos os valores que foram inseridos dentro das variáveis são parâmetros da aws.
-  Parâmetros da aws devem ser inseridos corretamente

Requerimentos:

**Download (https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-instances.html)**

2. ec2_cleaner.py= É uma receita em python que será utilizada para remover antigas máquinas virtuais que não serão utilizadas;

3. requirements.txt = Este arquivo é de extrema importância pois com ele você evita problemas de versão de python, boto, bibliotecas etc.. 
 - Veja o exemplo abaixo:
 
   $ pip install -r requirements.txt

4. Importante instalar o conda, pois ele permite que você tenha a versão do python certa no seu diretório.

Requerimentos:
**Download (https://docs.conda.io/en/latest/miniconda.html)**


$ conda create --name "robos-kroton" python=3.8

$ conda activate robos-kroton


## Iniciando...

$ `git clone `git clone git@github.com:1STi/cleaner.robos.kroton.git

$ `cd `cleaner.robos.kroton

Agora você poderá executar os vários comandos abaixo.

 Pré-requisitos

- `aws cli instalação pelo terminal --version`<br>
- A maneira mais segura de instalar o AWS CLI é usar pip em um virtualenv:
```bash

$ python -m pip install awscli
- Ou, se você não estiver instalando em um virtualenv, para instalar globalmente:
$ sudo python -m pip install awscli
- Ou para o seu usuário:
$ python -m pip install --user awscli

- Configure as credenciais da AWS
$ export AWS_ACCESS_KEY_ID="AKIAIQFALIN4NAHVS67A"
$ export AWS_SECRET_ACCESS_KEY="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"
- Importante também exportar a região
$ export AWS_REGION=us-east-1



##Finalizando o  projeto...
```bash
$ python3 nomedoarquivo.py
$ python3 cleaner.robos.kroton




