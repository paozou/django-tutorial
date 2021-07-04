# Overview

- DRFのチュートリアル

## 環境構築手順

```bash
cd /path/to/django_tutorial
python3 -m venv env
source env/bin/activate

pip install django
pip install djangorestframework
pip install pygments
```

## 動作確認手順

migrationは不要かも

```bash
python manage.py makemigrations snippets
python manage.py migrate

# サーバー起動
python manage.py runserver

# 別ターミナル情で
pip install httpie

# Go to http http://127.0.0.1:8000/snippets/
```
