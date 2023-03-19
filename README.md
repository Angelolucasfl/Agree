## <Pré-requisitos>  :computer:
Certifique-se de ter as seguintes ferramentas instaladas em sua máquina:
- Python
- pip 
- git

## Instalação:
### 1. Clone o repositório para sua máquina:

    git clone https://github.com/Angelolucasfl/Agree.git

### 2. Navegue até o diretório do projeto:

    cd Agree

### 3. Crie um ambiente virtual para o projeto:

    python -m venv venv

### 4. Ative o ambiente virtual:
  - Windows:
        
        venv\Scripts\activate
 
  - Linux/Mac:
           
        source venv/bin/activate

### 5. Instale as dependências do projeto:

    pip install -r requirements.txt
  
 ### 6. Execute as migrações do banco de dados:

    python manage.py migrate
 
 ### 7. Crie um superusuário:

    python manage.py createsuperuser

### 8. Inicie o servidor de desenvolvimento:

    python manage.py runserver


- Pronto! Agora você pode acessar o projeto em seu navegador em http://localhost:8000/.
