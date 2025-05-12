
# Schema Manager

This repository contains the django project, which is solely used for managing the migrations for an entire project. You can find the models for projects in `models` directory of `core_schema` app. Migrations files can be found inside `migrations` folder.

---

## 📁 Project Structure

``` bash
core_schema/
├── migrations/        # migration files
├── models/            # db models 
├── admin.py/          # admin panel configs 
schema_manager
├── settings.py        # django settings and configs
├── manage.py           # for managing django
requirements.txt    # Dependencies
```

## Creating new django model

1. Go to `models` directory of `core_schema`
2. To create models, select the service you want and add the required models. If the service you are looking for is not available then create one.
3. After creating models, register them to `admin.py` file, so that it's visible in django admin panel.

---
