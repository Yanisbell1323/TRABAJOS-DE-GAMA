<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>panel de administracion</title>
    <link rel="stylesheet" href="panel.css">
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    
  <div class="sidebar">
    <h4> Administracion</h4>
    <a href="panel.html">informacion de la empresa</a>
    <a href="nos.html">Nosotros</a>
    <a href="prod.html">Productos</a>
    <a href="rep.html">Reportes</a>
    <a href="form.html">Formulario</a>
  </div>

  <div class="main-content">
    <h2>Bienvenido al Panel de Monkey</h2>
    <p>Adminitracion de mi sitio </p>

    <div class="row">
      <div class="col-md-4">
        <div class="card text-white bg-primary mb-3">
          <div class="card-body">
            <h5 class="card-title">Usuarios</h5>
            <p class="card-text">Total: 124</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-white bg-success mb-3">
          <div class="card-body">
            <h5 class="card-title">Productos</h5>
            <p class="card-text">Total: 156</p>
          </div>
        </div>
      </div>
    </div>

  <section class="hero">
    <div class="container">
      <h1 class="display-4">Maquillaje Bella</h1>
      <p class="lead">Belleza real, poder real. Conecta con tu estilo, resalta tu esencia.</p>
    </div>
  </section>

  <section class="section bg-light">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6">
          <h3>Nuestra Historia</h3>
          <p>Fundada en 2020, Maquillaje Bella nació con la misión de brindar productos de alta calidad, accesibles y seguros para todo tipo de piel. Nos apasiona la innovación y creemos que el maquillaje debe empoderar, no esconder.</p>
        </div>
        <div class="col-md-6">
          <h3>Visión & Valores</h3>
          <p>Queremos ser líderes en cosmética ética e inclusiva. Nuestros valores: autenticidad, diversidad, respeto por el medio ambiente y compromiso con nuestros clientes.</p>
        </div>
      </div>
    </div>
  </section>


  <section class="section">
    <div class="container">
      <h3 class="text-center mb-5">¿Qué Ofrecemos?</h3>
      <div class="row g-4">
        <div class="col-md-4">
          <div class="icon-box shadow-sm">
            <h5>Productos de calidad</h5>
            <p>Base, labiales, sombras, delineadores y más... formulados para durar y cuidar tu piel.</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="icon-box shadow-sm">
            <h5>Atención personalizada</h5>
            <p>Asesoría para escoger el tono ideal o crear tu rutina de maquillaje diaria.</p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="icon-box shadow-sm">
            <h5>Compromiso social</h5>
            <p>No realizamos pruebas en animales. Apoyamos causas de empoderamiento femenino.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="bg-dark text-white text-center py-3">
    &copy; 2025 Maquillaje Bella. Todos los derechos reservados.
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Panel de administracion</title>
    <link rel="stylesheet" href="produc.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
</html>
<body>
 <div class="sidebar">
    <h4> Administracion</h4>
    <a href="panel.html">informacion de la empresa</a>
    <a href="nos.html">Nosotros</a>
    <a href="prod.html">Productos</a>
    <a href="rep.html">Reportes</a>
    <a href="form.html">Formulario</a>
  </div>

  <div class="main-content">
    <h2>Bienvenido al Panel de Monkey</h2>
    <p>Adminitracion de mi sitio </p>

  
    <div class="row">
      <div class="col-md-4">
        <div class="card text-white bg-primary mb-3 -">
          <div class="card-body">
            <h5 class="card-title">Usuarios</h5>
            <p class="card-text">Total: 124</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card text-white bg-success mb-3">
          <div class="card-body">
            <h5 class="card-title">Productos</h5>
            <p class="card-text">Total: 156</p>
          </div>
        </div>
      </div>
    </div>

</body>
</html>
  

  <div class="main-content">
    <div class="d-flex justify-content-between align-items-center mb-4">
      <h2>Productos de Maquillaje</h2>
      <button class="btn btn-success">+ Agregar Producto</button>
    </div>


    <div class="table-responsive">
      <table class="table table-striped table-hover align-middle">
        <thead class="table-dark">
          <tr>
            <th>ID</th>
            <th>Nombre</th>
            <th>Categoría</th>
            <th>Precio</th>
            <th>Stock</th>
            <th>Acciones</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>Base líquida</td>
            <td>Rostro</td>
            <td>$15.00</td>
            <td>40</td>
            <td>
              <button class="btn btn-sm btn-primary">Editar</button>
              <button class="btn btn-sm btn-danger">Eliminar</button>
            </td>
          </tr>
          <tr>
            <td>2</td>
            <td>Labial mate</td>
            <td>Labios</td>
            <td>$8.00</td>
            <td>85</td>
            <td>
              <button class="btn btn-sm btn-primary">Editar</button>
              <button class="btn btn-sm btn-danger">Eliminar</button>
            </td>
          </tr>
          <tr>
            <td>3</td>
            <td>Sombras 12 tonos</td>
            <td>Ojos</td>
            <td>$12.50</td>
            <td>30</td>
            <td>
              <button class="btn btn-sm btn-primary">Editar</button>
              <button class="btn btn-sm btn-danger">Eliminar</button>
            </td>
          </tr>
         
        </tbody>
      </table>
    </div>
  </div>

  <footer class="bg-dark text-white text-center py-3">
    &copy; 2025 Maquillaje Bella. Todos los derechos reservados.
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> panel de administracion</title>
    <link rel="stylesheet" href="rep.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    
  <div class="sidebar">
    <h4>Administracion</h4>
    <a href="panel.css">informacion de la empresa</a>
    <a href="prod.html">Productos</a>
    <a href="rep.html" >Reportes</a>
    <a href="form.html">formulario</a>
  </div>

 
  <div class="main-content">
    <h2 class="mb-4">Reportes de Maquillaje</h2>

    <div class="row mb-4">
      <div class="col-md-4">
        <div class="card bg-primary text-white text-center p-3">
          <h5>Total de Productos</h5>
          <p class="fs-3">36</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card bg-success text-white text-center p-3">
          <h5>Stock Disponible</h5>
          <p class="fs-3">280 unidades</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card bg-warning text-dark text-center p-3">
          <h5>Categorías</h5>
          <p class="fs-5">Rostro, Labios, Ojos</p>
        </div>
      </div>
    </div>
    <h4>Resumen por categoría</h4>
    <table class="table table-bordered mt-3">
      <thead class="table-dark">
        <tr>
          <th>Categoría</th>
          <th>Productos</th>
          <th>Stock Total</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Rostro</td>
          <td>12</td>
          <td>90</td>
        </tr>
        <tr>
          <td>Labios</td>
          <td>14</td>
          <td>110</td>
        </tr>
        <tr>
          <td>Ojos</td>
          <td>10</td>
          <td>80</td>
        </tr>
      </tbody>
    </table>
  </div>
    
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>panel de administracion</title>
    <link rel="stylesheet" href="nos.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
       <a href="panel.html" class="btn btn-outline-primary mt-4">
  ← Volver a la Página Principal
</a>

     <!-- Sección principal -->
  <section class="hero">
    <div class="container">
      <h1>Sobre Nosotros</h1>
      <p class="lead">Somos apasionados por el maquillaje y la belleza. Nuestro objetivo es ofrecer productos de alta calidad y una experiencia única a nuestras clientas.</p>
    </div>
  </section>

  <!-- Historia / Misión -->
  <section class="section bg-light">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6">
          <img src="fc4a2233-1f7d-4752-bd92-a1f7e007e9a5.jpeg" alt="Historia" class="team-img mb-4 mb-md-0">
        </div>
        <div class="col-md-6">
          <h3>Nuestra Historia</h3>
          <p>Desde el 2020, nuestra empresa ha trabajado para brindar productos innovadores, seguros y asequibles en el mundo del maquillaje. Creemos en la inclusión, la diversidad y el poder de la expresión personal a través de la belleza.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container text-center">
      <h3 class="mb-5">Nuestro Equipo</h3>
      <div class="row">
        <div class="col-md-4 mb-4">
          <img src="çec,-c.jpeg" alt="Ana" class="rounded-circle mb-3" width="250" height="250">
          <h5>Anamelo Gómez</h5>
          <p>Fundadora & CEO</p>
        </div>
        <div class="col-md-4 mb-4">
          <img src="descarga (14).jpeg" alt="Laura" class="rounded-circle mb-3" width="250" height="250">
          <h5>Laurana Pérez</h5>
          <p>Directora de Marketing</p>
        </div>
        <div class="col-md-4 mb-4">
          <img src="descarga (15).jpeg" alt="Rosa" class="rounded-circle mb-3" width="250" height="250">
          <h5>Rosamelo Díaz</h5>
          <p>Jefa de Producto</p>
        </div>
      </div>
    </div>
  </section>


  <footer class="bg-dark text-white text-center py-3">
    &copy; 2025 Maquillaje Bella. Todos los derechos reservados.
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>panel de administraciob</title>
    <link rel="stylesheet" href="form.css">
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  </head>
</head>
<body>
<a href="panel.html" class="btn btn-outline-primary mt-4">
  ← Volver a la Página Principal
</a>
  </div>
  <div class="center-container">
    <div class="form-box">
      <h4 class="mb-4 text-center">Formulario de Contacto</h4>
      <form>
        <div class="mb-3">
          <input type="text" class="form-control" placeholder="Nombre completo " required>
        </div>
        <div class="mb-3">
          <input type="fecha de nacimiento" class="form-control" placeholder="Fecha de nacimiento" required>
        </div>
         <div class="mb-3">
          <input type="telefono" class="form-control" placeholder="telefono" required>
        </div>
         <div class="mb-3">
          <input type=" mujer , hombre o personalizado" class="form-control" placeholder="Genero " required>
        </div>
         <div class="mb-3">
          <input type="" class="form-control" placeholder="Profesion" required>
        </div>
         <div class="mb-3">
          <input type="email" class="form-control" placeholder="Correo" required>
        </div>
         <div class="mb-3">
          <input type="contraseña" class="form-control" placeholder="Contraseña" required>
        </div>
        <div class="mb-3">
          <textarea class="form-control" rows="3" placeholder="Mensaje" required></textarea>
        </div>
        <button type="submit" class="btn btn-primary w-100">Enviar</button>
      </form>
    </div>
  </div>
  </div>
 
  <footer class="bg-dark text-white text-center py-3">
    &copy; 2025 Maquillaje Bella. Todos los derechos reservados.
  </footer>
</body>
</html>
