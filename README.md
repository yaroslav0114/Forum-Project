Forum Project developed by Kevin

cd ..
git clone https://github.com/liuhuipy/djangoblog.git
(dgblog) [root@VM_85_24_centos PyProjects]# ls
DjangoUeditor3  djangoblog
(dgblog) [root@VM_85_24_centos PyProjects]# cd djangoblog/
(dgblog) [root@VM_85_24_centos djangoblog]# ls
README.md  djangoblog  media             static
apps       manage.py   requirements.txt  templates
(dgblog) [root@VM_85_24_centos djangoblog]# pip install -r requirements.txt
(dgblog) [root@VM_85_24_centos djangoblog]# pip list                #列表下载的python包
Django (1.10.4)
django-crispy-forms (1.6.1)
django-debug-toolbar (1.8)
django-formtools (2.0)
django-haystack (2.6.1)
djangorestframework (3.6.3)
DjangoUeditor (1.8.143)
future (0.16.0)
httplib2 (0.10.3)
humanize (0.5.1)
olefile (0.44)
Pillow (4.2.1)
pip (9.0.1)
setuptools (36.0.1)
sqlparse (0.2.3)
wheel (0.29.0)
```
```
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser             
python manage.py runserver          
```

