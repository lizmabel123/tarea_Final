Se debe hacer un archivo local_settings.py para la base de datos (en este caso postgresql), dentro del texto solo se debe poner lo siguiente:

DATABASES = {
    'default': {
        'ENGINE': "django.db.backends.postgresql",
        'NAME': 'el nombre de tu db',
        'USER': 'el user de tu db',
        'PASSWORD': 'la contraseña de tu db',
        'HOST': '127.0.0.1',
        'PORT': '5432',
    }
}  
