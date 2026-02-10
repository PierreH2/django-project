


```bash
sudo apt install python3-venv -y

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

django-admin startproject ll_project .
python3 manage.py migrate
python3 manage.py runserver
python3 manage.py startapp learning_logs


python3 XXX.py

```