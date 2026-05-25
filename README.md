# Proyecto EIF-208 - Comunicaciones y Redes 2026

Aplicación web simple en Flask desplegada con Docker, GitHub Actions y AKS.

## Cómo correr localmente

```bash
pip install -r requirements.txt
python app.py
```

## Con Docker

```bash
docker build -t proyecto-redes .
docker run -p 5000:5000 proyecto-redes
```

Luego abrís http://localhost:5000 en el navegador.