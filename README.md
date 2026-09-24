# 🌈 GoGuay 🚗✨  

**La app de movilidad compartida pensada para la comunidad LGBTQ+.**  

GoGuay nace con el objetivo de crear un espacio seguro, inclusivo y diverso en los viajes compartidos.  
Queremos que moverse no sea solo cuestión de llegar de un punto A a un punto B, sino de hacerlo en un entorno de confianza, respeto y comunidad.  

---

## 🚀 ¿Qué es GoGuay?
GoGuay es una aplicación inspirada en modelos como BlaBlaCar, pero con un enfoque totalmente inclusivo y orientado a la comunidad LGBTQ+.  

A través de la app, podrás:  
- 👥 Compartir coche con personas que comparten valores de respeto y diversidad.  
- 🔒 Viajar en un entorno seguro, donde la identidad y la orientación de cada persona son respetadas.  
- 🌍 Conectar con una comunidad que busca una movilidad más sostenible e inclusiva.  
- 💸 Ahorrar en tus viajes y contribuir al cuidado del medio ambiente.  

---

## 🛠️ Tecnologías utilizadas
- **Frontend:** Ionic / Angular  
- **Backend:** Python (Flask)  
- **Base de datos:** Supabase (PostgreSQL)  
- **Infraestructura:** Docker & Render  

---

## 👩‍💻👨‍💻 ¿Quiénes somos?
GoGuay es un proyecto desarrollado con pasión y compromiso por dos personas que creen en la importancia de la inclusión en todos los ámbitos de la vida — también en la movilidad.  

- **Daniel G.D.** → Full Stack Developer.  
   

- **[Juan Tomás P.H.]** → Full Stack Developer.  
   


---

## 🌟 Nuestra misión
Construir una alternativa de movilidad que no solo sea funcional y cómoda,  
sino que además refuerce valores de respeto, inclusión y diversidad.  

En GoGuay creemos que **viajar también puede ser un acto de orgullo**. 🌈  

---

## 📸 Preview
![Registro screenshot](image.png)  

---

## 🤝 Contribuir
GoGuay está abierto a ideas, feedback y colaboración.  
Si quieres aportar, ¡escríbenos!  


---

## [	GUÍA PYTHON		]

-> Comandos para crear las migraciones sin necesidad de crear un entorno virtual:
	- Tienes que estar ubicado en el directorio /backend para que estos funcionen.
	- Si ya has ejecutado el comoando "db init" este ya no es necesario volver a ejecutarlo
	  cada vez que quieras actualizar las migraciones, solo es necesario la primera vez.
	  

    python -m flask db init
    python -m flask db migrate -m "Corregir relaciones con claves foráneas ambiguas"
    python -m flask db upgrade
	
	
	*** NOTA: Si aparece el error que no encuentra una versión anterior, seguir los siguientes pasos:
		- Eliminar el directorio 'migrations'
		- Eliminar el directorio '__pycache__'



python app.py




# Comando para construir build para DOCKER DESKTOP
"Es necesario tener la aplicación "Docker Desktop" iniciada.
Con el siguiente comando se crea una build del proyecto recogiendo los datos de backend.
Es necesario ejecutar este comando desde la carpeta backend donde está el fichero "dockerfile""

docker build -t prideride .
