1. Crear virtual environment
`python -m venv .venv`

2. Activar virtual environment
`.venv\Scripts\Activate.ps1`

3. Instalar paquetes
`pip install "fastapi[standard]" `

4. Crear archivo requirements.txt
`python -m pip freeze > requirements.txt`

5. Crear main.py
6. Correr servidor `fastapi dev app/main.py`

7. En Azure el comando para iniciar la app en producción es:
`fastapi run app/main.py`

8. Instalar Testclient
`pip install httpx`
9. Instalar pytest
`pip install pytest`

