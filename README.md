[estilos.css](https://github.com/user-attachments/files/24797137/estilos.css)
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #fff0f5;
    text-align: center;
}

header {
    background-color: #e91e63;
    color: white;
    padding: 20px;
}

.galeria {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 15px;
    padding: 20px;
}

.galeria img {
    width: 100%;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

footer {
    background-color: #f8bbd0;
    padding: 10px;
    font-size: 14px;
}
.whatsapp-float {
  position: fixed;
  width: 60px;
  height: 60px;
  bottom: 30px;
  right: 30px;
  background-color: #25D366;
  color: white;
  border-radius: 50%;
  text-align: center;
  font-size: 30px;
  line-height: 60px;
  box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
  z-index: 100;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.whatsapp-float:hover {
  background-color: #1ebe5d;
}

[index.html](https://github.com/user-attachments/files/24797143/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Uñas by [Nombre]</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>

    <header>
        <h1>Uñas by [Nombre]</h1>
        <p>Diseños profesionales y personalizados</p>
    </header>

    <section class="galeria">
        <img src="imagenes/unas1.jpg" alt="Diseño de uñas 1">
        <img src="imagenes/unas2.jpg" alt="Diseño de uñas 2">
        <img src="imagenes/unas3.jpg" alt="Diseño de uñas 3">
    </section>

    <footer>
        <p>📍 Citas por WhatsApp | © 2026</p>
<a class="btn-whatsapp" 
   href="https://wa.me/34667191839" 
   target="_blank">
   💬 Agendar cita por WhatsApp
href="https://wa.me/34667191839?text=Hola%20quiero%20agendar%20una%20cita%20para%20embellecer%20mis%20uñas"

</a>![unas1](https://github.com/user-attachments/assets/28586a0b-575a-40fc-a489-6ae9280979d4)
![unas4](https://github.com/user-attachments/assets/d61672e2-e565-483d-9589-6194852a1bd0)
![unas3](https://github.com/user-attachments/assets/4f283787-95a3-4f1b-8fa9-ac1119effa81)
![unas2](https://github.com/user-attachments/assets/ab8df3b6-3ce5-4884-aa7b-160f7b5a2cb2)


    </footer>
<a href="https://wa.me/34667191839" target="_blank" class="whatsapp-float">
  💬
</a>

</body>
</html>

