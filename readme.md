Instalar docker desktop
  https://www.docker.com/products/docker-desktop/
Instalar python na store do windows 
  Store está no menu ininiar
Instalar dbeaver
  https://dbeaver.io/download/


comandos
  cd backend
  python -m venv env
  env\Scripts\activate
  (env)pip install -r requirements.txt
  docker compose up -d
  (env)python main.py


O front usaria isso apos criar os arquivos
cd frontend
npm install
npm run start
ir para http://localhost:3000

docker compose up -d


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
