# python

#### Instalando Python no Ubuntu.

```
sudo apt-get install python3
```

#### Verificando a instalação

```
python --version
```
ou
```
python3 --version
```

#### Instalando pip, gerenciador de pacotes

```
sudo apt-get install python3-pip
```

#### Verificando a instalação do pip

```
pip --version
```
ou
```
pip3 --version
```

#### Instalando venv, gerenciador de ambiente virtual 

```
sudo apt-get install python3-venv
```

#### Iniciando um ambiente virtual

```
python3 -m venv .venv
```

1. ```-m venv``` importa o módulo do venv
2. ```.venv``` é o diretório onde desejamos criar esse ambiente

#### Ativando um ambiente virtual

```
source .venv/bin/activate
```

#### Saindo do ambiente virtual

```
deactivate
```

#### Instalando pacotes

```
pip install <nome do pacote>
```
exemplo de instalação do pacote numpy
```
pip install numpy
```

#### Listando os pacotes instalados

```
pip list
```

#### No Python é comum listar as dependências do projeto em um arquivo ```requirements.txt```. Assim outros desenvolvedores conseguem instalar as mesmas bibliotecas que você.

#### Listando todos os pacotes instalados no formato ````requirements.txt```

```
pip freeze
```

#### Instalando pacotes a partir do ````requirements.txt```

```
pip install -r requirements.txt
```





