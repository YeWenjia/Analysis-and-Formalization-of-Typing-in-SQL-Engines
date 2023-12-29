# eSeQueeLe

1. install the docker-desktop

2. In the artifact folder, there is a folder named: dockers 

3. go to that folder and run : `docker-compose up -d`

4. pull and run the DB using host NET : `docker pull wenjiaye/db:v1` and `docker run -it --net host --name db wenjiaye/db:v1 bash`

5. cd to home: `cd home` 

6. activate the python environment: `source py39/bin/activate`

7. cd to test folder: `cd py_Interpreter/test`

8. run test file by changing the engine's name:`PYTHONPATH=../ pytest test_postgres.py` (test_postgres.py,test_mysql.py,test_mssql.py,test_oracle.py,test_sqlite.py)









