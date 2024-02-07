# DjangoQuotesV3

tutaj działa, jeszcze nad tym pracuję

## Instalacja

1. Sklonuj repozytorium: `git clone https://github.com/Camilleus/DjangoQuotesV3.git`
2. Przejdź do folderu projektu: `cd DjangoQuotesV3`
3. Zainstaluj zależności: `poetry install`
4. Uruchom serwer: `poetry run python manage.py runserver`

## Przyszłe Rozszerzenia

Top Ten Tags
Ulubione Cytaty

## Struktura Projektu

```
DjangoQuotesV4
├─ .gitattributes
├─ notes
│  ├─ data_baser.py
│  ├─ manage.py
│  ├─ media
│  │  ├─ author_images
│  │  │  ├─ 2565830.jpg
│  │  │  ├─ 370279477_1076899290336339_2682171693873150376_n.jpg
│  │  │  ├─ 3837194.jpg
│  │  │  ├─ 4105635.jpg
│  │  │  ├─ 419882478_1517151512416851_6516303177956484248_n.jpg
│  │  │  ├─ 4TTR2YkP72hO2Gk26XKTma7O0v02FMpj.jpg
│  │  │  └─ FB_IMG_1604499348697.jpg
│  │  ├─ default_avatar.png
│  │  └─ profile_images
│  │     ├─ 370279477_1076899290336339_2682171693873150376_n.jpg
│  │     ├─ 411221090_211111158707645_1322271260579833626_n.jpg
│  │     ├─ download.png
│  │     └─ MOHoPbHH0zs0eiZeIlfP8Ntvf9f7Q5KO.png
│  ├─ noteapp
│  │  ├─ admin.py
│  │  ├─ apps.py
│  │  ├─ forms.py
│  │  ├─ migrations
│  │  │  ├─ 0001_initial.py
│  │  │  ├─ 0002_remove_quote_author_remove_quote_user_note_user_and_more.py
│  │  │  ├─ 0003_tag_tags.py
│  │  │  └─ __init__.py
│  │  ├─ models.py
│  │  ├─ static
│  │  │  └─ noteapp
│  │  │     ├─ modern-normalize.css
│  │  │     └─ styles.css
│  │  ├─ templates
│  │  │  └─ noteapp
│  │  │     ├─ base.html
│  │  │     ├─ detail.html
│  │  │     ├─ index.html
│  │  │     ├─ note.html
│  │  │     ├─ notes_by_tag.html
│  │  │     └─ tag.html
│  │  ├─ templatetags
│  │  │  └─ extract_tags.py
│  │  ├─ urls.py
│  │  ├─ views.py
│  │  └─ __init__.py
│  ├─ notes
│  │  ├─ asgi.py
│  │  ├─ settings.py
│  │  ├─ urls.py
│  │  ├─ wsgi.py
│  │  └─ __init__.py
│  ├─ quotes
│  │  ├─ admin.py
│  │  ├─ apps.py
│  │  ├─ forms.py
│  │  ├─ migrations
│  │  │  ├─ 0001_initial.py
│  │  │  ├─ 0002_author_description_author_image.py
│  │  │  ├─ 0003_tag_alter_author_description.py
│  │  │  └─ __init__.py
│  │  ├─ models.py
│  │  ├─ templates
│  │  │  └─ quotes
│  │  │     ├─ add_author.html
│  │  │     ├─ add_quote.html
│  │  │     ├─ author.html
│  │  │     ├─ author_detail.html
│  │  │     ├─ quote.html
│  │  │     └─ quote_detail.html
│  │  ├─ urls.py
│  │  ├─ views.py
│  │  └─ __init__.py
│  ├─ quotes.json
│  ├─ scrapper.py
│  ├─ sqlite3.db
│  └─ users
│     ├─ admin.py
│     ├─ apps.py
│     ├─ auths.py
│     ├─ forms.py
│     ├─ migrations
│     │  ├─ 0001_initial.py
│     │  └─ __init__.py
│     ├─ models.py
│     ├─ signals.py
│     ├─ templates
│     │  └─ users
│     │     ├─ login.html
│     │     ├─ profile.html
│     │     └─ signup.html
│     ├─ urls.py
│     ├─ views.py
│     └─ __init__.py
├─ poetry.lock
├─ pyproject.toml
├─ quotes.json
└─ README.md
```
