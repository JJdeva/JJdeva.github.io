---
layout: post
title: "[django] django 공부 02"
categories: django
tags: [django]
---
# django 시작하기

## django project 생성

<br>
django project를 시작해보자.
우선 python, django 버전 체크

```bash
> python -V
Python 3.10.1
> pip show django | grep Version
Version: 4.0
```

<br>

프로젝트의 루트 디렉토리를 만들자.
```bash
> mkdir django_web
> cd django_web
```

<br>
루트 디렉토리에 이제 프로젝트를 생성해보자. (프로젝트명 : config)

```bash
> django-admin startproject config .
```

<br>

django의 기본 디렉토리 구조

```bash
django_web/
  ├── config/
  │  ├── __init__.py
  │  ├── asgi.py
  │  ├── settings.py
  │  ├── urls.py
  │  └── wsgi.py
  └── manage.py
```
