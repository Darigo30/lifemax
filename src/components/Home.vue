<template>
  <b-container class="alto-min" fluid>
    <b-row class="alto-min">
      <b-col cols="12" md="6" class="p-0 alto-min">
        <div class="img-woman"></div>
      </b-col>

      <b-col cols="12" md="6" class="d-flex align-items-center log-t-i alto-min">
        <b-container>
          <b-row>
            <b-col cols="12">
              <div
                class="logo-text d-flex flex-column align-items-center mx-auto">
                <img src="../assets/logo.png" />
                <h1 class="text-uppercase mt-3 text-lg-right text-center">
                  Accesorios + servicio técnico para dispositivos móviles
                </h1>
              </div>
            </b-col>
            <b-col cols="12">
              <h2 class="py-4 text-center">
                Buscamos proteger, mejorar y prolongar la vida de cualquier
                dispositivo móvil
              </h2>
            </b-col>
            <b-row class="pt-4 no-gutters">
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" v-b-modal.modal-center>
                  <div class="btn-rrss-icon ov-btn-grow-skew">Sitio Web</div>
                  <div class="iconos"><i class="fas fa-globe"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" v-b-modal.modal-whats>
                  <div class="btn-rrss-icon ov-btn-grow-skew">WhatsApp</div>
                  <div class="iconos"><i class="fab fa-whatsapp"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" v-b-modal.modal-surc>
                  <div class="btn-rrss-icon ov-btn-grow-skew">Sucursales</div>
                  <div class="iconos"><i class="fas fa-map-marked-alt"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" href="https://www.facebook.com/lifemax.cll/" target="_blank">
                  <div class="btn-rrss-icon ov-btn-grow-skew">Facebook</div>
                  <div class="iconos"><i class="fab fa-facebook-f"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" href="https://www.instagram.com/lifemax.cl/?igshid=8i55gwoo9do2" target="_blank">
                  <div class="btn-rrss-icon ov-btn-grow-skew">Instagram</div>
                  <div class="iconos"><i class="fab fa-instagram"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" href="#">
                  <div class="btn-rrss-icon ov-btn-grow-skew">TikTok</div>
                  <div class="iconos"><i class="fab fa-tiktok"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" href="https://eshops.mercadolibre.cl/lifemax" target="_blank">
                  <div class="btn-rrss-icon ov-btn-grow-skew">Mercado Libre</div>
                  <div class="iconos"><i class="fas fa-store"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" href="https://www.linio.cl/s/lifemax-" target="_blank">
                  <div class="btn-rrss-icon ov-btn-grow-skew">Linio</div>
                  <div class="iconos"><i class="fas fa-store"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" href="https://lifemax.mercadoshops.cl/" target="_blank">
                  <div class="btn-rrss-icon ov-btn-grow-skew">MercadoShop</div>
                  <div class="iconos"><i class="fas fa-store"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="6">
                <a class="d-flex btn-rrss" href="mailto:ventas@lifemaxstore.cl">
                  <div class="btn-rrss-icon ov-btn-grow-skew">Email</div>
                  <div class="iconos"><i class="far fa-envelope"></i></div>
                </a>
              </b-col>
              <b-col cols="12" md="12">
                <a class="d-flex btn-rrss" v-b-modal.modal-catal>
                  <div class="btn-rrss-icon ov-btn-grow-skew">Catálogo de Productos</div>
                  <div class="iconos"><i class="fas fa-file-pdf"></i></div>
                </a>
              </b-col>
            </b-row>
          </b-row>
          <b-row>
            <b-col cols="12">
              <div class="d-flex justify-content-center align-items-center">
                <i class="fas fa-map-marker-alt"></i>
                <a
                  href="https://www.google.com/maps/place/LifeMax+-+Accesorios+%2B+Servicio+Tecnico+Celulares/@-33.4466041,-70.6529295,17z/data=!3m1!4b1!4m5!3m4!1s0x9662c5e0bff76e9f:0xae2f1f634db6247f!8m2!3d-33.4466033!4d-70.650731"
                  target="_blank"
                  class="ms-2"
                  >Santiago de Chile</a
                >
              </div>
            </b-col>
            <b-col cols="12">
              <div class="text-center pt-3">
                Copyright © 2019. Todos los derechos reservados
              </div>
            </b-col>
          </b-row>
        </b-container>
      </b-col>
    </b-row>
    <!-- Modales-->
    <!-- Modal Sitios Web-->
    <b-modal id="modal-center" v-bind:hide-footer="true" class="titlemodal" centered title="Sitios Web">
      <div class="my-4">
        <a class="d-flex btn-rrss-modal" href="https://www.lifemaxstore.cl" target="_blank">
          <div class="btn-rrss-icon ov-btn-grow-skew">Ventas Detalle</div>
          <div class="iconos"><i class="fas fa-globe"></i></div>
        </a>
        <a class="d-flex btn-rrss-modal" href="https://www.lifemaxdistribuidora.cl" target="_blank">
          <div class="btn-rrss-icon ov-btn-grow-skew">Ventas Mayoristas</div>
          <div class="iconos"><i class="fas fa-globe"></i></div>
        </a>
      </div>
    </b-modal>
    <!-- Modal Whatsapp-->
    <b-modal id="modal-whats" v-bind:hide-footer="true" class="titlemodal" centered title="WhatsApp">
      <div class="my-4">
        <a class="d-flex btn-rrss-modal" href="https://wa.me/56966263774" target="_blank">
          <div class="btn-rrss-icon ov-btn-grow-skew">Ventas Detalle</div>
          <div class="iconos"><i class="fab fa-whatsapp"></i></div>
        </a>
        <a class="d-flex btn-rrss-modal" href="https://wa.me/message/ZJ6JGUXRFXXRP1" target="_blank">
          <div class="btn-rrss-icon ov-btn-grow-skew">Ventas Mayor</div>
          <div class="iconos"><i class="fab fa-whatsapp"></i></div>
        </a>
      </div>
    </b-modal>
    <!-- Modal Sucursales-->
    <b-modal id="modal-surc" v-bind:hide-footer="true" class="titlemodal" centered title="Sucursales">
      <div class="my-4">
        <a class="d-flex btn-rrss-modal" href="https://www.google.com/maps/place/LifeMax+-+Accesorios+%2B+Servicio+Tecnico+Celulares/@-33.4466041,-70.6529295,17z/data=!3m1!4b1!4m5!3m4!1s0x9662c5e0bff76e9f:0xae2f1f634db6247f!8m2!3d-33.4466033!4d-70.650731" target="_blank">
          <div class="btn-rrss-icon ov-btn-grow-skew">Matriz</div>
          <div class="iconos"><i class="fas fa-map-marked-alt"></i></div>
        </a>
        <a class="d-flex btn-rrss-modal" href="https://www.google.com/maps/place/LifeMax+-+Accesorios+%2B+Servicio+Tecnico+Celulares/@-33.4466041,-70.6529295,17z/data=!3m1!4b1!4m5!3m4!1s0x9662c5e0bff76e9f:0xae2f1f634db6247f!8m2!3d-33.4466033!4d-70.650731" target="_blank">
          <div class="btn-rrss-icon ov-btn-grow-skew">Sucursal</div>
          <div class="iconos"><i class="fas fa-map-marked-alt"></i></div>
        </a>
      </div>
    </b-modal>
    <!-- Modal Catálogo de productos-->
    <b-modal id="modal-catal" v-bind:hide-footer="true" class="titlemodal" centered title="Catálogo de Productos">
      <div class="my-4">
        <a class="d-flex btn-rrss-modal" href="http://lifemax-store.cl/archivos/catalagodeRepuestoLifemax.pdf" target="_blank">
          <div class="btn-rrss-icon ov-btn-grow-skew">Repuestos</div>
          <div class="iconos"><i class="fas fa-file-pdf"></i></div>
        </a>
        <a class="d-flex btn-rrss-modal" href="http://lifemax-store.cl/archivos/catalogoaccesorioslifemax.pdf" target="_blank">
          <div class="btn-rrss-icon ov-btn-grow-skew">Accesorios</div>
          <div class="iconos"><i class="fas fa-file-pdf"></i></div>
        </a>
        <a class="d-flex btn-rrss-modal" href="http://lifemax-store.cl/archivos/cataalogo-computacion-lifemax.pdf" target="_blank">
          <div class="btn-rrss-icon ov-btn-grow-skew">Computación</div>
          <div class="iconos"><i class="fas fa-file-pdf"></i></div>
        </a>
      </div>
    </b-modal>
  </b-container>
</template>

<script>
export default {
  name: "Home",
};
</script>
