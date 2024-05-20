<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda de Mascotas</title>
  <style>
    body {
      background-color: #ffefd5; /* melocotón */
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    .header {
      background-color: #ffefd5; /* melocotón */
      padding: 20px 0;
      border-bottom: 5px solid #ff4500; /* naranja rojizo */
    }
    .header h1 {
      font-size: 2.5em;
      font-weight: bold;
      margin: 0;
      color: #ff4500; /* naranja rojizo */
      text-shadow: 2px 2px 4px #f0f0f0; /* Sombra ligera para dar profundidad */
    }
    .header p {
      font-size: 1.2em;
      color: #555;
      text-align: center;
    }
    nav {
      background-color: #f0f0f0;
      padding: 10px;
      text-align: right;
    }
    nav a {
      color: #008000;
      text-decoration: none;
      margin: 0 10px;
      padding: 5px 10px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    nav a:hover {
      color: #fff;
      background-color: #006600;
    }
    section {
      background-color: #ffffe0;
      padding: 20px;
      margin: 20px;
      border: 1px solid #ccc;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    
   table {
        width: 100%;
        border-collapse: collapse;
    }
    th, td {
        border: 1px solid #ddd;
        padding: 8px;
        text-align: left;
    }
    th {
        background-color: #ff8c00; /* Naranja */
        color: white;
    }
    tr:nth-child(even) {
        background-color: #b0e0e6; /* Azul claro */
    }
    tr:hover {
        background-color: #f5f5f5;
    }

    th, td {
      padding: 15px;
      text-align: left;
      border-bottom: 1px solid #ddd;
    }
    th {
      background-color: #ff6347;
      color: white;
    }
    td {
      background-color: #e0ffff;
    }
    tr:hover {
      background-color: #f5f5f5;
    }
    .email-link {
      color: #ff69b4;
      text-decoration: none;
    }
    .email-link:hover {
      color: #ff33cc;
    }
    form {
      background-color: #f0e68c;
      padding: 20px;
      margin: 20px;
      border: 1px solid #ccc;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    footer {
      background-color: #f5f5dc;
      padding: 10px;
      text-align: center;
      clear: both;
    }
  </style>
</head>
<body>

  <header class="header">
    <h1>¡Bienvenidos a Nuestra Tienda de Mascotas!</h1>
    <p>Encuentra el compañero perfecto para tu familia</p>
  </header>
    <nav>
    <a href="#perros">Perros</a> |
    <a href="#gatos">Gatos</a> |
    <a href="#contacto">Contáctanos</a>
  </nav>
<section id="adopcion">
    <h2>Centro de Adopción "Amigos Fieles"</h2>
    <p><strong>Ubicación:</strong> Estado de mexico, Coacalco</p>
    <iframe
  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3762.909377688634!2d-99.1685976850933!3d19.427024986888215!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85d1ff505617b1e3%3A0x205e3b7b3817b73a!2sZ%C3%B3calo%2C%20Plaza%20de%20la%20Constituci%C3%B3n%20S%2FN%2C%20Centro%2C%20Cuauht%C3%A9moc%2C%2006000%20Ciudad%20de%20M%C3%A9xico%2C%20CDMX!5e0!3m2!1ses!2smx!4v1617893625479!5m2!1ses!2smx"
  width="600"
  height="450"
  style="border:0;"
  allowfullscreen=""
  loading="lazy">
</iframe>
    <p><strong>Horario de Atención:</strong> Lunes a Viernes de 9:00 a 18:00, Sábados de 10:00 a 14:00</p>
    <p>En "Amigos Fieles", nuestro objetivo es encontrar un hogar amoroso y permanente para cada mascota que rescatamos. Creemos que todos los animales merecen una segunda oportunidad y trabajamos incansablemente para asegurarnos de que cada uno de ellos sea adoptado por una familia que les brinde el cuidado y la atención que necesitan.</p>
    <p>Ofrecemos servicios de adopción responsables, asesoramiento para nuevos propietarios y seguimiento post-adopción para garantizar el bienestar de nuestras mascotas y la satisfacción de las familias.</p>
    <p>Si estás interesado en adoptar, visita nuestra sección de <a href="#mascotas-para-adopcion">Mascotas para Adopción</a> o contáctanos para más información.</p>
  </section>


  

  <!-- Secciones de perros y gatos... -->
<section id="perros">
    <h2>Nuestros Perros</h2>
    <ul>
      <li>
        <h3>Golden Retriever</h3>
        <p>El Golden Retriever es una raza de perro de tamaño grande, originaria de Escocia. Son conocidos por su pelaje dorado y su personalidad amigable y leal. Son excelentes mascotas para familias con niños, ya que son muy pacientes y tolerantes.</p>
      </li>
      <li>
        <h3>Labrador</h3>
        <p>El Labrador es una raza de perro de tamaño grande, originaria de Canadá. Son conocidos por su pelaje negro, amarillo ochocolate y su personalidad activa y juguetona. Son excelentes mascotas para familias activas, ya que requieren mucho ejercicio y estimulación mental.</p>
      </li>
      <li>
        <h3>Beagle</h3>
        <p>El Beagle es una raza de perro de tamaño mediano, originaria de Inglaterra. Son conocidos por su pelaje tricolor y su personalidad amigable y curiosa. Son excelentes mascotas para familias con niños, ya que son muy juguetones y aman jugar y correr.</p>
      </li>
    </ul>
    <p>Ver imágenes de Golden Retriever en <a href="https://www.purina.es/encuentra-mascota/razas-de-perro/golden-retriever">Google</a></p>
  </section>

  <section id="gatos">
    <h2>Nuestros Gatos</h2>
    <ul>
      <li>
        <h3>Persa</h3>
        <p>El Persa es una raza de gato de tamaño mediano, originaria de Persia. Son conocidos por su pelaje largo y sedoso y su personalidad tranquila y relajada. Son excelentes mascotas para personas que buscan un compañero tranquilo y cariñoso.</p>
      </li>
      <li>
        <h3>Maine Coon</h3>
        <p>El Maine Coon es una raza de gato de tamaño grande, originaria de Estados Unidos. Son conocidos por su pelaje largo y denso y su personalidad activa y juguetona. Son excelentes mascotas para familias activas, ya que requieren mucho ejercicio y estimulación mental.</p>
      </li>
      <li>
        <h3>Ragdoll</h3>
        <p>El Ragdoll es una raza de gato de tamaño grande, originaria de Estados Unidos. Son conocidos por su pelaje semilargo y su personalidad dulce y cariñosa. Son excelentes mascotas para personas que buscan un compañero tranquilo y cariñoso.</p>
      </li>
    </ul>
    <p>Ver imágenes de Persian Cat en <a href="https://unsplash.com/es/s/fotos/persian-cat">Google</a></p>
  </section>
<body>

<h2>Mascotas en Adopción</h2>

<table>
    <tr>
        <th>Tipo de Mascota</th>
        <th>Raza</th>
        <th>Nombre</th>
        <th>Edad</th>
    </tr>
    <tr>
        <td>Perro</td>
        <td>Labrador</td>
        <td>Max</td>
        <td>2 años</td>
    </tr>
    <tr>
        <td>Gato</td>
        <td>Siames</td>
        <td>Luna</td>
        <td>1 año</td>
    </tr>
    <!-- Agrega más filas según sea necesario -->
</table>

  <!-- Sección de contacto... -->
<section id=contacto> 
<form action="enviar.php" method="post" onsubmit="alert('Enviado');">
    <!-- Campos del formulario -->
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" required><br>
    <label for="email">Correo electrónico:</label>
    <input type="email" id="email" name="email" required><br>
    <label for="mensaje">Mensaje:</label>
    <textarea id="mensaje" name="mensaje" required></textarea><br>
    <input type="submit" value="Enviar">
  </form>
  </section>
  <footer>
    <p>© 2023 Nuestra Tienda de Mascotas. Todos los derechos reservados.</p>
  </footer>

</body>
</hml>
