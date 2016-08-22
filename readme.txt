Para realizar la conexion a base de datos mysql desde python en windows
pip install wheel
pip install pymysql

En settings.py
import pymysql
pymysql.install_as_MySQLdb()
