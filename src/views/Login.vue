<script setup>
import Header from '../components/Header.vue'
import { FormKit } from '@formkit/vue'
</script>

<template>
    <Header />
    <div class="centrar-form container">
        
        <div class="titulo-Login">
            <h2>Tecnologico Nacional de Mexico Campus Acapulco</h2>
            <img src="../Img/logo-ita.png" alt="">
        </div>
        
        <div class="formulario">
            <div>
                <h2 class="titulo-sesion">Iniciar Sesión</h2>
                <img src="../Img/logo-ita.png" alt="">
            </div>
            <FormKit type="form">
                <FormKit type="text" label="Correo Electronico" placeholder="Ingresa tu correro electronico"
                    suffixIcon="email" />
                <FormKit type="password" label="Contraseña" placeholder="Ingresa tu contraseña" suffixIcon="password" />
            </FormKit>
        </div>
    </div>
</template>