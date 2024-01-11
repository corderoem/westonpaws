# westonpaws
1. Requisitos Previos
- Git: Para clonar los repositorios.
- Node.js y npm: Necesarios para los proyectos React.
- Python: Necesario para Django.
- Pip: Gestor de paquetes de Python para instalar dependencias de Django.
- Venv Para crear un entorno virtual en Python.
2. Clonar Repositorios y Configuración Inicial
1. Clonar Repositorios
1. Frontend:
git clone https://gitlab.com/xavia-weston-spa/frontend.git
cd frontend
npm install
2. Admin-Portal:
git clone https://gitlab.com/xavia-weston-spa/admin-portal.git
cd admin-portal 
npm install
3. Backend:
git clone https://gitlab.com/xavia-weston-spa/backend.git
cd backend
npm install
2. Configurar el Backend (Django)
1. Crear y Activar un Entorno Virtual (Opcional):
python -m venv venv
source venv/bin/activate 
# En Windows usa
venv\Scripts\activate
2. Instalar Dependencias:
pip install -r requirements.txt
3. d. Ejecutar el Servidor de Desarrollo:
python manage.py runserver
3. Configuración de Proyectos React
1. Ejecutar Aplicaciones React
1. Frontend
cd frontend 
npm start
2. Admin-Portal
cd admin-portal 
npm start
4. Consideraciones Finales
- Variables de Entorno: Si tu aplicación utiliza variables de entorno, asegúrate de configurarlas
adecuadamente en cada proyecto.
- Pruebas: Realiza pruebas para asegurarte de que cada servicio se conecta y funciona como se 
espera.
- Documentación Adicional: Cada proyecto puede tener especificaciones o pasos adicionales
únicos para ese proyecto. Consulta la documentación individual de cada repositorio para más 
detalles