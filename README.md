# 015_FetchRewards_HW
Solution for Fetch Rewards Coding Exercise - Analytics Engineer



conda requirement:
There is bug in sqlalchemy 1.4.5 that causes the following error:
```
MetaData.__init__() got an unexpected keyword argument 'bind'
Connection info needed in SQLAlchemy format, example:
               postgresql://username:password@hostname/dbname
               or an existing connection: dict_keys([])
```
So the best 
 - `python = 3.7`
 - `conda install sqlalchemy==1.4.4`
 - `conda install conda-forge::ipython-sql`
 - `conda install conda-forge::psycopg2-binary`