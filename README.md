# DJANGO REST FRAMEWORK를 이용한 CRUD 샘플
참고 : [Django REST framework](http://www.django-rest-framework.org/) 

## Requirements
- Python 3.12.x
- Django 3.x
- Django REST Framework

## Installation
가상환경 설정
```
python -m venv env
```

필요한 라이브러리 설치
```
pip install -r requirements.txt
```

## 구조
Endpoint |HTTP Method | CRUD Method | Result
-- | -- |-- |--
`movies` | GET | READ | Get all movies
`movies/:id` | GET | READ | Get a single movie
`movies`| POST | CREATE | Create a new movie
`movies/:id` | PUT | UPDATE | Update a movie
`movies/:id` | DELETE | DELETE | Delete a movie

## 테스트 방법
포스트맨에 'python.postman_collection.json'를 import 하여 테스트

