# Next + Redux + Django REST Framework Blog Project

> This is a blog full stack project based on Nextjs, Redux, and Django REST Framework.
> If you like this project, please do not forget to give a star!

### TODO:

- advertising module

## Preview

### Front End

**Home Page**
![image-20191025143441031](./preview/frontend1.png)

**Article Page**
![image-20191025143441031](./preview/frontend2.png)

### Admin

![image-20191025143441031](./preview/admin1.png)

![image-20191025143441031](./preview/admin2.png)

## Run in local

1. git clone project

```
git clone https://github.com/honey0120/django-next.js-blog.git
```

2. server side

```
cd server
source ./venv/bin/activate          // enter virtual environment (linux or mac)
pip install django djangorestframework pillow  // install dependencies
python3 manage.py makemigrations    // migrate database
python3 manage.py migrate
python3 manage.py createsuperuser   // create admin superuser
python3 manage.py runserver         // run django development server
```

3. front end side

```
cd front end
yarn add  or  npm install           // install dependencies
yarn dev  or  npm run dev           // run project
```

## Tech Stack

- Next.js
- Ant Design UI
- Redux
- Redux Devtools Extension
- React Redux
- Django REST Framework
- React Markdown
- Markdown Navbar
- Moment
