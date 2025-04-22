# Projeto - APP Mobile + Rest API com Python e Django  

## Configuração do Ambiente

### Criação do ambiente virtual:  

**Linux**  
```bash
python3 -m venv venv
```
**Windows**
```bash
python -m venv venv
```

## Ativação do ambiente:

**Linux**
```bash
source venv/bin/activate
```
**Windows**
```bash
venv\Scripts\Activate
```

### Solução para erro de permissão no Windows:
```bash
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```
 
## Instalação e Configuração
```bash
pip install flet  
pip install requests
```

## Execução da aplicação

### Opções para rodar o app
```bash
flet run app.py
``` 
```bash
python app.py
```
```bash
python3 app.py
```
