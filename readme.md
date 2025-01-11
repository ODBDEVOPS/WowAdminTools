# Start Project WowAdminTools
**Step 1: install Django**
``` python
    pip install Django  

    Collecting Django
    Using cached Django-5.1.4-py3-none-any.whl.metadata (4.2 kB)
    Collecting asgiref<4,>=3.8.1 (from Django)
    Using cached asgiref-3.8.1-py3-none-any.whl.metadata (9.3 kB)
    Collecting sqlparse>=0.3.1 (from Django)
    Using cached sqlparse-0.5.3-py3-none-any.whl.metadata (3.9 kB)
    Collecting tzdata (from Django)
    Using cached tzdata-2024.2-py2.py3-none-any.whl.metadata (1.4 kB)
    Using cached Django-5.1.4-py3-none-any.whl (8.3 MB)
    Using cached asgiref-3.8.1-py3-none-any.whl (23 kB)
    Using cached sqlparse-0.5.3-py3-none-any.whl (44 kB)
    Using cached tzdata-2024.2-py2.py3-none-any.whl (346 kB)
    Installing collected packages: tzdata, sqlparse, asgiref, Django
    Successfully installed Django asgiref sqlparse tzdata
```
**Step 2: Create a new Django project WowAdminTools**
``` python
    django-admin startproject WowAdminTools
```
**Step 3: Create a new Django app within the project**
``` bash
    cd .\WowAdminTools\
```

``` python
    # Section wow_web - Index
    py manage.py startapp wow_web
    # Section wow_web - wow_db
    py manage.py startapp wow_db_srvside
    py manage.py startapp wow_db_cltside
    # Section wow_web - wow_World
    py manage.py startapp wow_World_Adt 
    py manage.py startapp wow_World_Wdt
    py manage.py startapp wow_World_Wdl
```

# Source
[wowdev.wiki](https://wowdev.wiki/Main_Page)
# wow_web
[text](.wiki_md/wow_web/wow_web.md)
# wow_db_srvside
[text](.wiki_md/wow_db/wow_db_srvside/wow_db_srvside.md)
# wow_db_cltside
[text](.wiki_md/wow_db/wow_db_cltside/wow_db_cltside.md)




# wow_World_Adt
[text](.wiki_md/wow_World/wow_World_Adt/wow_World_Adt.md)
# wow_World_Wdt
[text](.wiki_md/wow_World/wow_World_Wdl/wow_World_Wdl.md)
# wow_World_Wdl
[text](.wiki_md/wow_World/wow_World_Wdt/wow_World_Wdt.md)
# BE03727s DEVOPs
[text](.wiki_md/BE_Devops/Integration_Via_Json.md)
[text](.wiki_md/BE_Devops/spell-basics.md)