# Instalar docker desktop
  https://www.docker.com/products/docker-desktop/
<br \>Instalar python na store do windows 
  <br \>Store está no menu ininiar
<br \>Instalar dbeaver
  <br \>https://dbeaver.io/download/


# comandos api
  cd backend
  python -m venv env
  env\Scripts\activate
  (env)pip install -r requirements.txt
  docker compose up -d
  ver se a conexao funciona
  (env)python main.py
  testar endpoints no localhost:8002\docs
  parar main da api
# comandos db
  cd banckend
  cd db
  (env)python main.py
  ver se a tabela foi criada no dbeaver
  testar endpoints no localhost:8002\docs
  



O front usaria isso apos criar os arquivos
cd frontend
npm install
npm run start
ir para http://localhost:3000




exemplos de conexões
# postgree modo 1
engine = create_engine("postgresql://scott:tiger@localhost/mydatabase")

# postgree modo 2 psycopg2
engine = create_engine("postgresql+psycopg2://scott:tiger@localhost/mydatabase")

# mysql
engine = create_engine("mysql://scott:tiger@localhost/foo")
")
# sql server
engine = create_engine("mssql+pymssql://scott:tiger@hostname:port/dbname")
