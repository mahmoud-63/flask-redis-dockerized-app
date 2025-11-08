# Flask Redis Web App 

This is a simple **Flask-based web application** that tracks the number of visits using **Redis** as a backend key-value store.  
It displays the visit count dynamically on a styled HTML page.

---

##  Project Structure

- `app.py`: Flask backend script (not authored by me).
- `templates/index.html`: Frontend HTML page (not authored by me).
- `static/styles.css`: Styling for the HTML (not authored by me).
- `Dockerfile`: Docker image for the Flask app 
- `docker-compose.yml`: Docker Compose configuration to run both Flask and Redis containers 

---

##  What I Did

I am responsible for:

- Writing the **Dockerfile** to containerize the Flask application.
- Creating the **`docker-compose.yml`** file to connect the Flask app with a Redis container.
- Structuring the project for Docker-based deployment.
- Testing and ensuring the containers work seamlessly together.

>  **Note:** I did not write the Python (`app.py`), HTML (`index.html`), or CSS (`styles.css`) code. These were provided as templates for the project.

---

##  How to Run the Project

Make sure Docker and Docker Compose are installed.  
Then, from the project root:

```bash
docker compose up -d --build
```
Visit http://localhost:9000 to see the app in action
