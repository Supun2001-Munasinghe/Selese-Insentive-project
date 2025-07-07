#How to run the backend
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
cd Sales_Incentive
cd backend
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver



#push command to bitbucket
git add .
git commit -m"##Your comment##"
git push origin main


# change to ranch
git checkout branch

git push origin branch