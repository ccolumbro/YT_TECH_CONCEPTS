# BIT&CUBIT Tours API

##Características
- CRUD completo de reservas
- Seguridad con API Key
- Documentación Swagger en `/docs`
- Base de datos SQLite
- Código limpio y modular

##Cómo ejecutar
1. Instalar dependencias:
```bash
pip install -r requirements.txt
```

2.Inicializar base de datos:
```bash
python -c "from app.database import init_db; init_db()"
```

3.Ejecutar el servidor:
```bash
uvicorn app.main:app --reload
```

4.Probar en Swagger UI:
[http://localhost:8000/docs](http://localhost:8000/docs)