# Crear Entrono Virtual
```
 python -m venv venv
```
# Activar Entorno venv
```
 source venv/Scripts/activate
```
> [!IMPORTANT]  
> ```cd SmartSparking```
# Instalar Dependencias
```
 pip install -r requirements.txt
```
> [!TIP]
> Visualizar dependencias
> 
> ```pip freeze```

# Crear Super User

```
 python manage.py create superuser
```
# Migrar
```
 python manage.py makemigrations
```
```
 python manage.py migrate
```

# Ejecutar entorno
```
 python manage.py runserver
```
> [!IMPORTANT]  
> URL: http://127.0.0.1:8000/




