<template>
  <header class="bg-gradient-to-r from-cyan-400 to-cyan-400 py-4">
    <div class="container mx-auto flex justify-between items-center">
      <a href="#" class="text-white font-bold text-xl ml-2"
        >Gustavo Suarez - 2023</a
      >
      <nav>
        <a href="#" class="text-white hover:underline mx-4">Inicio</a>
        <a href="#" class="text-white hover:underline mx-4">Propuestas</a>
        <a href="#" class="text-white hover:underline mx-4">Contacto</a>
      </nav>
    </div>
  </header>

  <section class="bg-white py-6">
    <div class="container mx-auto">
      <h1 class="text-4xl font-bold mb-">
        Gustavo Suarez para Intendente 2023
      </h1>
      <p class="text-gray-700 text-lg mb-8">
        ¡Bienvenido a la página oficial de Gustavo Suarez para la candidatura a
        intendente de San José en 2023! En esta página podrás conocer sus
        propuestas, sus valores y su visión para el pueblo.
      </p>

      <img
        src="https://files.fm/thumb_show.php?i=79vmt8etn"
        alt="Foto de Gustavo Suarez"
        class="rounded-lg mb-4"
      />
    </div>
  </section>

  <section class="bg-cyan-300 py-16">
    <div class="container mx-auto">
      <h2 class="text-2xl font-bold mb-8">Nuestras Propuestas</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
        <div
          class="bg-white p-6 rounded-lg m-2"
          style="background-color: #fef08a"
        >
          <h3 class="text-lg font-bold mb-2">Educación de Calidad</h3>
          <p class="text-gray-700">
            Nos comprometemos a mejorar la calidad de la educación en San José,
            invirtiendo en infraestructuras y recursos para los centros
            educativos de la ciudad.
          </p>
        </div>
        <div
          class="bg-white p-6 rounded-lg m-3"
          style="background-color: #fcd34d"
        >
          <h3 class="text-lg font-bold mb-2">Desarrollo Económico</h3>
          <p class="text-gray-700">
            Promoveremos la creación de nuevas empresas y empleos en San José,
            fomentando la innovación y el desarrollo tecnológico en la ciudad.
          </p>
        </div>
        <div
          class="bg-white p-6 rounded-lg m-3"
          style="background-color: #fef08a"
        >
          <h3 class="text-lg font-bold mb-2">Seguridad Ciudadana</h3>
          <p class="text-gray-700">
            Trabajaremos en estrecha colaboración con la policía local para
            garantizar la seguridad y protección de todos los ciudadanos de San
            José.
          </p>
        </div>
      </div>
    </div>
  </section>

  <section class="bg-cool-gray-100 py-16">
    <div class="container mx-auto">
      <h2 class="text-2xl font-bold mb-">Sobre Gustavo Suarez</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <div class="card m-2">
          <img
            src="https://files.fm/thumb_show.php?i=6by97nk2e"
            alt="Foto de Gustavo Suarez"
            class="rounded-lg card"
          />
        </div>
        <div class="m-2">
          <div class="card">
            <p class="text-gray-700 text-lg mb-4">
              Gustavo Suarez es un destacado abogado y político de San José,
              comprometido con el desarrollo y el bienestar de su comunidad.
              Nació y creció en la ciudad, donde ha desempeñado un papel activo
              en la sociedad desde una temprana edad.
            </p>
            <p class="text-gray-700 text-lg mb-4">
              Es licenciado en Derecho por la Universidad Nacional de San José y
              ha trabajado en varios despachos de abogados locales antes de
              fundar su propio bufete en 2005. Desde entonces, ha defendido con
              éxito a numerosos clientes en casos de diversa índole.
            </p>
            <p class="text-gray-700 text-lg mb-4">
              En el ámbito político, Gustavo ha sido miembro del Concejo
              Municipal de San José durante dos mandatos consecutivos, donde ha
              luchado por los derechos de los ciudadanos y ha trabajado para
              mejorar la calidad de vida en la ciudad. Ahora, como candidato a
              la intendencia de San José, quiere llevar su compromiso y su
              experiencia a un nuevo nivel, para hacer de la ciudad un lugar
              mejor para todos.
            </p>
          </div>
          <a
            href="#"
            class="
              bg-blue-500
              hover:bg-blue-600
              text-white
              font-bold
              py-2
              px-4
              rounded
            "
            >Contacta con Gustavo</a
          >
        </div>
      </div>
    </div>
  </section>

  <footer class="bg-gradient-to-r from-blue-500 to-purple-500 text-white py-6">
    <div class="container mx-auto px-4">
      <p class="text-center">&copy; 2023. Gustavo Suárez Intendente 2023.</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Home',
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
  border-radius: 5px; /* ajusta este valor para modificar la curvatura de las esquinas de la tarjeta */
}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
}
</style>
