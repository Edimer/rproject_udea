---
title: Temas
layout: temas-moderno
---

<!-- Esta página ahora usa el layout moderno con tarjetas interactivas -->
<!-- Los datos se cargan dinámicamente desde JavaScript -->

<!-- Contenido de respaldo para navegadores sin JavaScript -->
<div class="no-js-fallback">
  <div class="container">
    <div class="alert alert-warning">
      <h4>¡Nueva Interfaz de Temas!</h4>
      <p>Hemos modernizado la sección de temas con un diseño más interactivo. Por favor, habilita JavaScript para disfrutar de la mejor experiencia.</p>
    </div>
    
    <h2>Temas de Estadística 2025</h2>
    <div class="legacy-topics">
      <div class="legacy-topic">
        <h3>Presentación del curso</h3>
        <p>Introducción al curso de Estadística 2025</p>
        <a href="/temas/Statistics-2025/01-curso/01-curso.html" class="btn btn-primary" target="_blank">Ver Diapositivas</a>
      </div>
      
      <div class="legacy-topic">
        <h3>Introducción a R y RStudio</h3>
        <p>Conceptos básicos de R y configuración del entorno</p>
        <a href="/temas/Statistics-2025/02-R-RStudio/01-r-rstudio.html" class="btn btn-primary" target="_blank">Ver Diapositivas</a>
      </div>
      
      <div class="legacy-topic">
        <h3>Datos ordenados</h3>
        <p>Tidy data y organización de conjuntos de datos</p>
        <a href="/temas/Statistics-2025/03-datos-ordenados/03-datos-ordenados.html" class="btn btn-primary" target="_blank">Ver Diapositivas</a>
        <a href="https://edimer.quarto.pub/ordenacion-de-datos/" class="btn btn-secondary" target="_blank">Ver Ejemplos</a>
      </div>

    </div>
    
    <h2>Temas de Diseño Experimental 2025</h2>
    <div class="legacy-topics">
      <div class="legacy-topic">
        <h3>Presentación del curso</h3>
        <p>Introducción al Diseño Experimental 2025</p>
        <a href="/temas/DisExperimental-2025/01-presentacion-curso.html" class="btn btn-primary" target="_blank">Ver Diapositivas</a>
      </div>
      
      <div class="legacy-topic">
        <h3>Introducción</h3>
        <p>Conceptos fundamentales de diseño experimental</p>
        <a href="/temas/DisExperimental-2025/02-introduccion.html" class="btn btn-primary" target="_blank">Ver Diapositivas</a>
      </div>
      
      <div class="legacy-topic">
        <h3>Regresión Lineal Simple</h3>
        <p>Análisis de regresión lineal simple</p>
        <a href="/temas/DisExperimental-2025/03-regresion-lineal-simple.html" class="btn btn-primary" target="_blank">Ver Diapositivas</a>
        <a href="https://edimer.quarto.pub/regresion-lineal-simple-1/" class="btn btn-secondary" target="_blank">Ver Ejemplos</a>
      </div>
    </div>
  </div>
</div>

<style>
.no-js-fallback {
  padding: 2rem 0;
}

.legacy-topics {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.legacy-topic {
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  border-radius: 8px;
  padding: 1.5rem;
}

.legacy-topic h3 {
  color: #1f2937;
  margin-bottom: 0.5rem;
}

.legacy-topic p {
  color: #64748b;
  margin-bottom: 1rem;
}

.legacy-topic .btn {
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
}

.alert {
  background: #fef3c7;
  border: 1px solid #fcd34d;
  border-radius: 8px;
  padding: 1rem;
  margin-bottom: 2rem;
}

.alert-warning {
  color: #92400e;
}

.alert h4 {
  color: #78350f;
  margin-bottom: 0.5rem;
}
</style>  
    
    