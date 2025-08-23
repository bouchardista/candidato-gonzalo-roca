<template>
  <div class="min-h-screen">
    <!-- Header -->
    <header class="relative z-10 bg-primary-950/80 backdrop-blur-sm">
      <nav class="px-16 md:px-32 py-6">
        <div class="flex items-center justify-center space-x-12 md:space-x-[30rem]">
          <div class="flex items-center">
            <h1 class="text-3xl md:text-4xl font-bold text-white whitespace-nowrap">Gonzalo Roca</h1>
          </div>
          <div class="flex items-center">
            <img src="/logo-alla.png" alt="Alianza La Libertad Avanza" class="h-16 sm:h-17 md:h-18 lg:h-19 xl:h-20 w-auto object-contain min-h-16 min-w-[100px]" />
          </div>
        </div>
      </nav>
    </header>

    <!-- Hero Section -->
    <section class="relative py-20 pb-8 px-4">
      <div class="container mx-auto">
        <div class="max-w-6xl mx-auto">
          <div class="grid md:grid-cols-2 gap-12 items-center">
            <!-- Contenido de texto -->
            <div class="text-left px-20 md:px-0">
              <p class="text-3xl md:text-5xl text-white/80 mb-8 leading-relaxed">
                Candidato a Diputado Nacional por la <strong>Alianza La Libertad Avanza</strong>
              </p>
              
              <p class="text-lg text-white/70 leading-relaxed mb-8">
                Junto a Javier Milei y Karina Milei estamos construyendo el futuro de Córdoba y de la Argentina. Cada día somos más los leones que nos despertamos para rugir contra la casta.
              </p>
              
              <p class="text-lg text-white/70 leading-relaxed mb-8">
                Seguime en mis redes para ser parte de esta batalla.
              </p>
              
              <div class="flex space-x-6 mb-8">
                <a href="https://x.com/roca_gon" target="_blank" class="text-white/80 hover:text-white transition-colors text-lg w-1/3 text-left">
                  <div><strong>X:</strong></div>
                  <div>@roca_gon</div>
                </a>
                <a href="https://www.instagram.com/gon.roca/" target="_blank" class="text-white/80 hover:text-white transition-colors text-lg w-1/3 text-left">
                  <div><strong>Instagram:</strong></div>
                  <div>@gon.roca</div>
                </a>
                <a href="https://fb.com/gonzalo.roca.18" target="_blank" class="text-white/80 hover:text-white transition-colors text-lg w-1/3 text-left">
                  <div><strong>Facebook:</strong></div>
                  <div>@gonzalo.roca.18</div>
                </a>
              </div>
            </div>
            
            <!-- Foto del candidato -->
            <div class="flex justify-center md:justify-end">
              <div class="relative">
                <img 
                  src="/gonzalo-roca.jpeg" 
                  alt="Gonzalo Roca" 
                  class="w-80 h-[450px] md:w-96 md:h-[550px] rounded-2xl object-cover shadow-2xl border-4 border-white/20"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Sobre el Candidato -->
    <!-- <section class="pt-12 pb-12 px-4">
      <div class="container mx-auto">
        <div class="max-w-4xl mx-auto">
          <h2 class="text-4xl font-bold text-white text-center mb-16">Sobre Gonzalo Roca</h2>
          
          <div class="space-y-8 text-white/80 text-lg leading-relaxed">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam auctor, nisl eget ultricies tincidunt, nisl nisl aliquam nisl, eget aliquam nisl nisl sit amet nisl. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </p>
            
            <p>
              Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
            </p>
            
            <p>
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.
            </p>
          </div>
        </div>
      </div>
    </section> -->

    <!-- Propuestas -->
    <!-- <section class="pt-12 pb-12 px-4">
      <div class="container mx-auto">
        <div class="max-w-4xl mx-auto">
          <h2 class="text-4xl font-bold text-white text-center mb-16">Propuestas Principales</h2>
          
          <div class="space-y-8">
            <div class="text-white/80">
              <h3 class="text-2xl font-semibold text-white mb-4">Desarrollo Económico</h3>
              <p class="text-lg leading-relaxed">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </p>
            </div>
            
            <div class="text-white/80">
              <h3 class="text-2xl font-semibold text-white mb-4">Educación</h3>
              <p class="text-lg leading-relaxed">
                Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
              </p>
            </div>
            
            <div class="text-white/80">
              <h3 class="text-2xl font-semibold text-white mb-4">Salud</h3>
              <p class="text-lg leading-relaxed">
                Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.
              </p>
            </div>
          </div>
        </div>
      </div>
    </section> -->

    <!-- Contacto -->
    <!-- 
    <section class="pt-12 pb-20 px-4">
      <div class="container mx-auto">
        <div class="max-w-2xl mx-auto text-center">
          <h2 class="text-4xl font-bold text-white mb-16">Contacto</h2>
          
          <div class="space-y-6 text-white/80">
            Información de contacto aquí si es necesaria
          </div>
        </div>
      </div>
    </section>
    -->

    <!-- Footer -->
    <footer class="py-12 px-4">
      <div class="container mx-auto text-center">
        <p class="text-white/60">
          © 2025 Alianza La Libertad Avanza. Todos los derechos reservados.
        </p>
      </div>
    </footer>
  </div>
</template>

<script setup>
useHead({
  title: 'Gonzalo Roca - Candidato a Diputado Nacional',
  meta: [
    { name: 'description', content: 'Conoce a Gonzalo Roca, candidato a Diputado Nacional. Conoce sus propuestas por una Córdoba más libre.' },
    { property: 'og:title', content: 'Gonzalo Roca - Candidato a Diputado Nacional' },
    { property: 'og:description', content: 'Conoce a Gonzalo Roca, candidato a Diputado Nacional. Conoce sus propuestas por una Córdoba más libre.' },
    { property: 'og:type', content: 'website' },
    { name: 'twitter:card', content: 'summary_large_image' },
    { name: 'twitter:title', content: 'Gonzalo Roca - Candidato a Diputado Nacional' },
    { name: 'twitter:description', content: 'Conoce a Gonzalo Roca, candidato a Diputado Nacional. Conoce sus propuestas por una Córdoba más libre.' }
  ]
})
</script>
