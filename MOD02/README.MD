# Coleta de Dados

## Ambiente Virtual

### Instalar Ambiente Virtual
```
pip install virtualenv
```
### Criar ambiente virtual
```
virtualenv -p python3 nome_ambiente_virtual
```
### Ativar ambiente virtual
```
nome_ambiente_virtual\Scripts\activate
```
* Obs.: No Windows, é necessário executar antes: 
```
Set-ExecutionPolicy Unrestricted -Scope Process
```

## PIP
### Listar pacotes instalados
```
pip list
```
### Importar pacotes instalados para requirements.txt
```
pip freeze > requirements.txt
```
### Instalar dependências do ambiente virtual
```
pip install -r requirements.txt
```