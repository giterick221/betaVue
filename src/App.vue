<template>
  <sidebar-menu :menu="menu" />
  <h1>REGISTRO DE COMMINATORIAS</h1>
  <div id="container">
    <form>
      <div class="form-group row">
        <label for="inputEmail3" class="col-sm-2 col-form-label"> CUD </label>
        <div class="col-sm-4">
          <input
            type="email"
            class="form-control"
            id="inputEmail3"
            placeholder="Email"
          />
        </div>
      </div>
      <div class="form-group row">
        <label for="inputPassword3" class="col-sm-2 col-form-label">
          Password
        </label>
        <div class="col-sm-4">
          <input
            type="password"
            class="form-control"
            id="inputPassword3"
            placeholder="Password"
          />
        </div>
      </div>
      <div class="form-group row">
        <label for="inputEmail3" class="col-sm-2 col-form-label"> NUREJ </label>
        <div class="col-sm-4">
          <input
            type="email"
            class="form-control"
            id="inputEmail3"
            placeholder="Email"
          />
        </div>
      </div>
      <div class="form-group row">
        <label for="inputEmail3" class="col-sm-2 col-form-label">
          DENUNCIANTE
        </label>
        <div class="col-sm-4">
          <input
            type="email"
            class="form-control"
            id="inputEmail3"
            placeholder="Email"
          />
        </div>
      </div>
      <div class="form-group row">
        <label for="inputEmail3" class="col-sm-2 col-form-label">
          DENUNCIADO
        </label>
        <div class="col-sm-4">
          <input
            type="email"
            class="form-control"
            id="inputEmail3"
            placeholder="Email"
          />
        </div>
      </div>
      <div class="form-group row">
        <label for="inputEmail3" class="col-sm-2 col-form-label">
          DELITO
        </label>
        <div class="col-sm-4">
          <input
            type="email"
            class="form-control"
            id="inputEmail3"
            placeholder="Email"
          />
        </div>
      </div>
      <div class="form-group row">
        <label for="inputEmail3" class="col-sm-2 col-form-label">
          FECHA NOTIFICACION C.D.
        </label>
        <div class="col-sm-4">
          <input
            type="email"
            class="form-control"
            id="inputEmail3"
            placeholder="Email"
          />
        </div>
      </div>
      <div class="form-group row">
        <label for="inputEmail3" class="col-sm-2 col-form-label">
          FECHA NOTIFICACION FISCAL
        </label>
        <div class="col-sm-4">
          <input
            type="email"
            class="form-control"
            id="inputEmail3"
            placeholder="Email"
          />
        </div>
      </div>
      <div class="form-group row">
        <label for="inputEmail3" class="col-sm-2 col-form-label">
          TIEMPO RESTANTE
        </label>
        <div class="col-sm-4">
          <input
            type="email"
            class="form-control"
            id="inputEmail3"
            placeholder="Email"
          />
        </div>
      </div>
      <div class="form-group row">
        <label for="inputEmail3" class="col-sm-2 col-form-label">
          REALIZADO
        </label>
        <div class="col-sm-4">
          <input
            type="email"
            class="form-control"
            id="inputEmail3"
            placeholder="Email"
          />
        </div>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      menu: [
        {
          header: "MENU",
          hiddenOnCollapse: true,
        },
        {
          href: "/",
          title: "INICIO",
          icon: "comment",
        },
        {
          title: "REGISTRAR",
          child: [
            {
              href: "/charts/sublink",
              title: "COMMINATORIA",
            },
            {
              href: "/charts/sublink",
              title: "FISCAL",
            },
          ],
        },
        {
          href: "/",
          title: "EDITAR COMMINATORIA",
        },
        {
          href: "/",
          title: "VER COMMINATORIAS",
        },
        {
          href: "/",
          title: "CERRAR SESION",
        },
      ],
    };
  },
  props: {
    width: {
      type: String,
      default: "1000px",
    },
  },
};
</script>
