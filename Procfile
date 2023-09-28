release: flask db upgrade
web: gunicorn upsun_cookies_5000.app:create_app\(\) -b 0.0.0.0:$PORT -w 3
