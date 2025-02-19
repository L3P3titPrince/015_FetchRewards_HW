# 015_FetchRewards_HW
Solution for Fetch Rewards Coding Exercise - Analytics Engineer


### Key File Explanations:
- **/src/FetchRewards_HW.ipynb**: Jupyter notebook version for this solution, you can download and connect to your local database to run.
- **/src/FetchRewards_HW.html**: HTML version of the Jupyter notebook, you can open it in your browser to view.

```markdown
## Project Structure

📁 015_FetchRewards_HW/
│
├── 📂 data/                            # Original Data files
│   └── 📄 *.sql                        # SQL backup scripts for data restore      
│   └── 📄 *.json                       # Original JSON data files
├── 📂 images/                          # Images for jupyter notebook
│
├── 📂 src/
│   ├── 📄 FetchRewards_HW.html         # HTML version of the Jupyter notebook
│   ├── 📄 FetchRewards_HW.ipynb        # Jupyter notebook solution
│
├── 📄 .gitignore                       # didn't upload
├── 📄 README.md                        # Project documentation
├── 📄 LICENSE                          # MIT
```




## conda requirement:
There is bug in sqlalchemy 1.4.5 that causes the following error:
```
MetaData.__init__() got an unexpected keyword argument 'bind'
Connection info needed in SQLAlchemy format, example:
               postgresql://username:password@hostname/dbname
               or an existing connection: dict_keys([])
```
So the best enviroment to run the code should be using:
 - `python = 3.7`
 - `conda install sqlalchemy==1.4.4`
 - `conda install conda-forge::ipython-sql`
 - `conda install conda-forge::psycopg2-binary`