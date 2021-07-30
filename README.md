# HSE_project

![badges](https://img.shields.io/badge/python-3.9-blue)
![badges](https://img.shields.io/badge/Django-3.2.4-yellow)

동국대학교 멋쟁이사자처럼 9 심바톤 3팀 HSE팀 (Hi-Sw-Education)

## Built With

- Team leader: [서희찬](https://github.com/seochan99)
- Team member: [박상준](https://github.com/tkdwns414), [이태검](https://github.com/LeeTaeGeom), [정민경](https://github.com/kkong1007)

## Installation

1. 터미널에 아래 내용 입력

```
git clone https://github.com/LikeLion-at-DGU/HSE_project.git
```

2. 가상환경 켜기

```
pipenv shell
```

3. Django 설치

```
pip install django
```

4. Django-allauth 설치

```
pip install django-allauth
```

5. Pillow 설치

```
pip install pillow
```

6. HSE_project 폴더 내에서 HSE 폴더로 이동

```
cd HSE
```

7. 모델의 변경내용 DB 스키마에 적용하기 위해 마이그레이션 생성

```
python manage.py makemigrations
```

8. DB에 마이그레이션 적용

```
python manage.py migrate
```

9. 실행

```
python manage.py runserver
```

### 봉사 등록 하고 싶은 경우 superuser를 생성하여 로그인
- superuser - 게시글 작성 및 수정 가능
- 일반 유저 - 신청만 가능

```
python manage.py createsuperuser
```

## Introduce

기존 봉사활동 참여를 위한 방식에서 

1. SNS를 통한 정형적이지 않는 교육자료 전달
2. 알 수 없는 교육 진행 날짜
3. 봉사 참여 학생에 제한된 교육 진행으로 인한 보조강사 몰림 현상
4. 체계적이지 않은 봉사 공지
5. 공평하지 않은 봉사 신청

과 같은 문제를 개선하고자

1. 봉사 안내 및 교육을 위한 게시글 작성 기능 
2. 일정 기간 동안 신청을 받고 무작위로 봉사자를 선정하는 기능
3. 개인 페이지를 통한 총 봉사활동 기록 확인 기능

등의 기능을 포함한 HI-SW-Education 페이지 구현을 목표로 하였다.
