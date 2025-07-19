<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Asesoría Universitaria</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Encabezado -->
  <header class="bg-blue-700 text-white shadow-md">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold">Asesorías U+</h1>
      <nav class="space-x-4">
        <a href="#servicios" class="hover:underline">Servicios</a>
        <a href="#contacto" class="hover:underline">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Hero principal -->
  <section class="bg-blue-100 py-16">
    <div class="max-w-4xl mx-auto text-center px-4">
      <h2 class="text-4xl font-bold mb-4">¿Listo para dar el siguiente paso?</h2>
      <p class="text-lg mb-6">Te ayudamos a elegir tu carrera ideal y a prepararte para tu ingreso a la universidad.</p>
      <a href="#contacto" class="bg-blue-700 text-white px-6 py-2 rounded-lg hover:bg-blue-800 transition">Solicita tu asesoría</a>
    </div>
  </section>

  <!-- Servicios -->
  <section id="servicios" class="py-16">
    <div class="max-w-6xl mx-auto px-4 text-center">
      <h3 class="text-3xl font-semibold mb-8">¿Qué ofrecemos?</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-white p-6 shadow-lg rounded-xl">
          <h4 class="text-xl font-bold mb-2">Orientación Vocacional</h4>
          <p>Te ayudamos a descubrir qué carrera se adapta mejor a tus intereses y habilidades.</p>
        </div>
        <div class="bg-white p-6 shadow-lg rounded-xl">
          <h4 class="text-xl font-bold mb-2">Asesoría de Ingreso</h4>
          <p>Te preparamos para los exámenes y procesos de admisión de las principales universidades.</p>
        </div>
        <div class="bg-white p-6 shadow-lg rounded-xl">
          <h4 class="text-xl font-bold mb-2">Talleres y Recursos</h4>
          <p>Accede a guías, talleres y simulacros gratuitos para tu desarrollo académico.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="bg-blue-50 py-16">
    <div class="max-w-3xl mx-auto px-4">
      <h3 class="text-3xl font-semibold text-center mb-8">Contáctanos</h3>
      <form class="bg-white shadow-md rounded-xl p-6 space-y-4">
        <input type="text" placeholder="Nombre completo" class="w-full px-4 py-2 border rounded-lg" required>
        <input type="email" placeholder="Correo electrónico" class="w-full px-4 py-2 border rounded-lg" required>
        <textarea placeholder="Mensaje o duda" class="w-full px-4 py-2 border rounded-lg h-32" required></textarea>
        <button type="submit" class="bg-blue-700 text-white px-6 py-2 rounded-lg hover:bg-blue-800 transition w-full">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Pie de página -->
  <footer class="bg-blue-700 text-white py-4 text-center">
    <p>&copy; 2025 Asesorías U+ | Todos los derechos reservados</p>
  </footer>

</body>
</html>
