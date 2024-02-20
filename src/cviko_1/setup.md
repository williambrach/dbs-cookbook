# Setup (only python)


### 1. Clone repository
```bash
git clone https://github.com/FIIT-Databases/dbs-python-example
```
### 2. Move to the repository
```bash
cd dbs-python-example
```
### 3. Install python 3.12 preferably
### 4. Create virtual environment
```bash
python -m venv venv
```
### 5. Activate virtual environment

MacOS/Linux
```bash
source venv/bin/activate
```
Windows
```bash
venv\Scripts\activate
```

### 6. Install requirements
```bash
pip install -r requirements.txt
```
if you have issues with installing requirements, install python 3.12 or good luck googling.


### 7. Run the code
```bash
uvicorn dbs_assignment.__main__:app --reload
```

### 8. Fix issues in code

* .env file is missing
* update config.py to support .env file

### 9. Work on the assignment

* FastAPI documentation: [https://fastapi.tiangolo.com/](https://fastapi.tiangolo.com/)
* Read README.md from: [https://github.com/FIIT-Databases/dbs-python-example](https://github.com/FIIT-Databases/dbs-python-example)
* Learn how to deploy assigmnet to tester.