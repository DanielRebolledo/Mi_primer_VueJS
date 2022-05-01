<template>
  <div>
    <h1></h1>
    <table class="table table-striped">
      <thead>
        <tr>
          <th>#</th>
          <th>Nombre</th>
          <th>Apellido</th>
          <th>RUN</th>
          <th>Nacimiento</th>
          <th>Edad</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>{{usuario1.nombre}}</td>
          <td>{{usuario1.apellido}}</td>
          <td>{{usuario1.run}}</td>
          <td>{{usuario1.nacimiento}}</td>
          <td>{{usuario1.edad}}</td>
        </tr>
        <tr>
          <td>2</td>
          <td>{{usuario2.nombre}}</td>
          <td>{{usuario2.apellido}}</td>
          <td>{{usuario2.run}}</td>
          <td>{{usuario2.nacimiento}}</td>
          <td>{{usuario2.edad}}</td>
        </tr>
        <tr>
          <td>3</td>
          <td>{{usuario3.nombre}}</td>
          <td>{{usuario3.apellido}}</td>
          <td>{{usuario3.run}}</td>
          <td>{{usuario3.nacimiento}}</td>
          <td>{{usuario3.edad}}</td>
        </tr>
      </tbody>
      
    </table>
  </div>
</template>

<script>

export default {
  name: 'App',
  data: () =>({

    usuario1 :{
        nombre: "Jose",
        apellido: "Perez",
        run: "12345678-9",
        nacimiento: "12-04-67",
        edad: 52
      },

      usuario2 :{
        nombre: "Maria",
        apellido: "Rodriguez",
        run: "12345678-9",
        nacimiento: "90-11-90",
        edad: 29
      },

      usuario3 :{
        nombre: "Manuel",
        apellido: "Patiño",
        run: "14223456-6",
        nacimiento: "02-12-59",
        edad: 60
      }
  }),
}
</script>

<style></style>
