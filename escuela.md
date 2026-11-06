<!DOCTYPE html>

<html lang="es" class="scroll-smooth">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Escuela Bahá'í | Educación Integral y Valores</title>

<!-- Tailwind CSS -->

<script src="https://cdn.tailwindcss.com"></script>

<!-- FontAwesome Icons -->

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

<!-- Google Fonts -->

<link rel="preconnect" href="https://fonts.googleapis.com">

<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Cinzel:wght@500;700&display=swap" rel="stylesheet">

<script>

tailwind.config = {

theme: {

extend: {

colors: {

bahai: {

blue: '#0F2C59',

sky: '#1E56A0',

gold: '#D4AF37',

amber: '#E8F5E9',

cream: '#F4F9F4', // Fondo verde claro suave y fresco

greenbg: '#EAF4EC', // Tono verde pastel sutil para secciones

accent: '#E0A96D'

}

},

fontFamily: {

sans: ['"Plus Jakarta Sans"', 'sans-serif'],

serif: ['Cinzel', 'serif']

}

}

}

}

</script>

<style>

.hero-gradient {

background: linear-gradient(135deg, rgba(15, 44, 89, 0.95) 0%, rgba(27, 94, 32, 0.85) 100%);

}

.star-pattern {

background-image: radial-gradient(rgba(212, 175, 55, 0.15) 1px, transparent 1px);

background-size: 24px 24px;

}

</style>

</head>

<body class="font-sans bg-bahai-cream text-slate-800 antialiased selection:bg-bahai-gold selection:text-bahai-blue">

<!-- Navegación Encabezado -->

<header class="fixed top-0 left-0 w-full bg-white/90 backdrop-blur-md shadow-sm z-50 transition-all duration-300" id="main-header">

<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">

<div class="flex justify-between items-center h-20">

<!-- Logo -->

<a href="#inicio" class="flex items-center space-x-3 group">

<div class="w-11 h-11 rounded-full bg-gradient-to-tr from-bahai-blue to-bahai-sky flex items-center justify-center shadow-md group-hover:scale-105 transition-transform duration-300">

<i class="fa-solid font-serif text-bahai-gold text-xl font-bold">9</i>

</div>

<div>

<span class="block font-serif text-xl font-bold text-bahai-blue tracking-wide">Escuela Bahá'í</span>

<span class="block text-xs text-bahai-sky font-medium tracking-wider uppercase">Unidad y Excelencia</span>

</div>

</a>

<!-- Menú Escritorio -->

<nav class="hidden md:flex items-center space-x-1 lg:space-x-2">

<a href="#inicio" class="px-4 py-2 rounded-full text-sm font-semibold text-slate-700 hover:text-bahai-blue hover:bg-bahai-amber transition-all">Inicio</a>

<a href="#actividades" class="px-4 py-2 rounded-full text-sm font-semibold text-slate-700 hover:text-bahai-blue hover:bg-bahai-amber transition-all">Actividades</a>

<a href="#curriculum" class="px-4 py-2 rounded-full text-sm font-semibold text-slate-700 hover:text-bahai-blue hover:bg-bahai-amber transition-all">Currículum</a>

<a href="#contacto" class="ml-2 px-5 py-2.5 rounded-full text-sm font-semibold bg-bahai-blue text-white hover:bg-bahai-sky shadow-md hover:shadow-lg transition-all transform hover:-translate-y-0.5">Contacto</a>

</nav>

<!-- Botón Menú Móvil -->

<button id="mobile-menu-btn" class="md:hidden p-2 rounded-lg text-slate-700 hover:bg-slate-100 focus:outline-none" aria-label="Abrir Menú">

<i class="fa-solid fa-bars text-2xl" id="menu-icon"></i>

</button>

</div>

</div>

<!-- Menú Desplegable Móvil -->

<div id="mobile-menu" class="hidden md:hidden bg-white border-b border-slate-100 shadow-xl">

<div class="px-4 pt-2 pb-6 space-y-2">

<a href="#inicio" class="mobile-link block px-4 py-3 rounded-xl text-base font-medium text-slate-700 hover:bg-bahai-amber hover:text-bahai-blue">Inicio</a>

<a href="#actividades" class="mobile-link block px-4 py-3 rounded-xl text-base font-medium text-slate-700 hover:bg-bahai-amber hover:text-bahai-blue">Actividades</a>

<a href="#curriculum" class="mobile-link block px-4 py-3 rounded-xl text-base font-medium text-slate-700 hover:bg-bahai-amber hover:text-bahai-blue">Currículum</a>

<a href="#contacto" class="mobile-link block px-4 py-3 rounded-xl text-base font-medium text-center bg-bahai-blue text-white hover:bg-bahai-sky">Contacto</a>

</div>

</div>

</header>

<!-- Sección Inicio / Héroe -->

<section id="inicio" class="relative pt-24 pb-20 lg:pt-32 lg:pb-32 overflow-hidden flex items-center min-h-screen">

<div class="absolute inset-0 bg-[url('https://images.unsplash.com/photo-1509062522246-3755977927d7?q=80&w=1600&auto=format&fit=crop')] bg-cover bg-center"></div>

<div class="absolute inset-0 hero-gradient"></div>

<div class="absolute inset-0 star-pattern opacity-40"></div>

<div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-white z-10">

<div class="inline-flex items-center space-x-2 px-4 py-2 rounded-full bg-white/10 backdrop-blur-md border border-white/20 mb-6 animate-pulse">

<i class="fa-solid fa-star text-bahai-gold text-xs"></i>

<span class="text-xs sm:text-sm font-medium tracking-wider text-bahai-amber uppercase">Educación para el servicio a la humanidad</span>

</div>

<h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tight font-serif mb-6 leading-tight">

Considerad al hombre como una <span class="text-transparent bg-clip-text bg-gradient-to-r from-bahai-gold via-amber-200 to-amber-400">mina rica en gemas</span>

</h1>

<p class="max-w-3xl mx-auto text-lg sm:text-xl text-slate-200 font-light leading-relaxed mb-10">

En la Escuela Bahá'í cultivamos el desarrollo intelectual, moral y espiritual. Nuestra misión es revelar las facultades latentes de cada estudiante para transformar positivamente la sociedad.

</p>

<div class="flex flex-col sm:flex-row justify-center gap-4 sm:gap-6">

<a href="#actividades" class="px-8 py-4 rounded-full bg-bahai-gold text-bahai-blue font-bold text-base shadow-lg hover:bg-yellow-400 hover:shadow-xl transition-all transform hover:-translate-y-1 text-center">

Descubrir Actividades

</a>

<a href="#curriculum" class="px-8 py-4 rounded-full bg-white/10 backdrop-blur-md border border-white/30 text-white font-semibold text-base hover:bg-white/20 transition-all text-center">

Conocer Modelo Educativo

</a>

</div>

<!-- Destacados breves -->

<div class="mt-16 grid grid-cols-1 sm:grid-cols-3 gap-6 text-left max-w-4xl mx-auto">

<div class="bg-white/10 backdrop-blur-md p-6 rounded-2xl border border-white/15">

<i class="fa-solid fa-seedling text-2xl text-bahai-gold mb-3"></i>

<h3 class="font-bold text-lg mb-1">Educación Moral</h3>

<p class="text-xs text-slate-300">Desarrollo de virtudes universales como la veracidad, compasión y justicia.</p>

</div>

<div class="bg-white/10 backdrop-blur-md p-6 rounded-2xl border border-white/15">

<i class="fa-solid fa-globe text-2xl text-bahai-gold mb-3"></i>

<h3 class="font-bold text-lg mb-1">Unidad en la Diversidad</h3>

<p class="text-xs text-slate-300">Fomento del respeto intercultural y conciencia de ciudadanía global.</p>

</div>

<div class="bg-white/10 backdrop-blur-md p-6 rounded-2xl border border-white/15">

<i class="fa-solid fa-microscope text-2xl text-bahai-gold mb-3"></i>

<h3 class="font-bold text-lg mb-1">Ciencia y Espiritualidad</h3>

<p class="text-xs text-slate-300">Armonía entre la investigación científica y el crecimiento moral.</p>

</div>

</div>

</div>

</section>

<!-- Sección Actividades -->

<section id="actividades" class="py-24 bg-white/80 relative">

<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">

<div class="text-center max-w-3xl mx-auto mb-16">

<h2 class="text-xs font-bold uppercase tracking-widest text-emerald-700 mb-2">Vida Escolar Dinámica</h2>

<p class="text-3xl sm:text-4xl font-serif font-bold text-bahai-blue mb-4">Nuestras Actividades Destacadas</p>

<div class="w-16 h-1 bg-bahai-gold mx-auto rounded-full mb-6"></div>

<p class="text-slate-600 leading-relaxed">

Promovemos un aprendizaje integral mediante proyectos prácticos, expresión artística y servicio activo a la comunidad local.

</p>

</div>

<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

<!-- Tarjeta 1 -->

<div class="group bg-bahai-greenbg rounded-3xl overflow-hidden border border-emerald-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-2 flex flex-col">

<div class="relative h-48 overflow-hidden">

<img src="https://images.unsplash.com/photo-1577896851231-70ef18881754?q=80&w=800&auto=format&fit=crop" alt="Talleres de Valores" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">

<span class="absolute top-4 right-4 bg-bahai-blue text-bahai-gold text-xs px-3 py-1 rounded-full font-bold shadow">Valores</span>

</div>

<div class="p-6 flex-1 flex flex-col justify-between">

<div>

<h3 class="text-xl font-bold text-bahai-blue mb-2 group-hover:text-emerald-700 transition-colors">Talleres de Virtudes Moral</h3>

<p class="text-slate-600 text-sm mb-4 leading-relaxed">

Espacios interactivos donde los alumnos reflexionan y aplican valores humanos en situaciones del día a día.

</p>

</div>

<div class="pt-4 border-t border-emerald-200/60 flex justify-between items-center text-xs text-slate-500">

<span><i class="fa-regular fa-clock mr-1"></i> Semanal</span>

<span><i class="fa-solid fa-users mr-1"></i> Todos los grados</span>

</div>

</div>

</div>

<!-- Tarjeta 2 -->

<div class="group bg-bahai-greenbg rounded-3xl overflow-hidden border border-emerald-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-2 flex flex-col">

<div class="relative h-48 overflow-hidden">

<img src="https://images.unsplash.com/photo-1544717305-2782549b5136?q=80&w=800&auto=format&fit=crop" alt="Proyectos Comunitarios" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">

<span class="absolute top-4 right-4 bg-bahai-blue text-bahai-gold text-xs px-3 py-1 rounded-full font-bold shadow">Servicio</span>

</div>

<div class="p-6 flex-1 flex flex-col justify-between">

<div>

<h3 class="text-xl font-bold text-bahai-blue mb-2 group-hover:text-emerald-700 transition-colors">Proyectos de Acción Social</h3>

<p class="text-slate-600 text-sm mb-4 leading-relaxed">

Iniciativas lideradas por estudiantes para el cuidado ambiental, reforestación y apoyo a comedores locales.

</p>

</div>

<div class="pt-4 border-t border-emerald-200/60 flex justify-between items-center text-xs text-slate-500">

<span><i class="fa-regular fa-calendar mr-1"></i> Mensual</span>

<span><i class="fa-solid fa-hand-holding-heart mr-1"></i> Impacto Social</span>

</div>

</div>

</div>

<!-- Tarjeta 3 -->

<div class="group bg-bahai-greenbg rounded-3xl overflow-hidden border border-emerald-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-2 flex flex-col">

<div class="relative h-48 overflow-hidden">

<img src="https://images.unsplash.com/photo-1513364776144-60967b0f800f?q=80&w=800&auto=format&fit=crop" alt="Arte y Música" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">

<span class="absolute top-4 right-4 bg-bahai-blue text-bahai-gold text-xs px-3 py-1 rounded-full font-bold shadow">Creatividad</span>

</div>

<div class="p-6 flex-1 flex flex-col justify-between">

<div>

<h3 class="text-xl font-bold text-bahai-blue mb-2 group-hover:text-emerald-700 transition-colors">Artes Creativas y Música</h3>

<p class="text-slate-600 text-sm mb-4 leading-relaxed">

Expresión a través de la pintura, la música coral y el teatro, fortaleciendo el espíritu y la sensibilidad.

</p>

</div>

<div class="pt-4 border-t border-emerald-200/60 flex justify-between items-center text-xs text-slate-500">

<span><i class="fa-regular fa-clock mr-1"></i> 2x por Semana</span>

<span><i class="fa-solid fa-palette mr-1"></i> Taller Expresivo</span>

</div>

</div>

</div>

<!-- Tarjeta 4 -->

<div class="group bg-bahai-greenbg rounded-3xl overflow-hidden border border-emerald-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-2 flex flex-col">

<div class="relative h-48 overflow-hidden">

<img src="https://images.unsplash.com/photo-1567168544813-cc03465b4fa8?q=80&w=800&auto=format&fit=crop" alt="Ferias Científicas" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">

<span class="absolute top-4 right-4 bg-bahai-blue text-bahai-gold text-xs px-3 py-1 rounded-full font-bold shadow">Ciencia</span>

</div>

<div class="p-6 flex-1 flex flex-col justify-between">

<div>

<h3 class="text-xl font-bold text-bahai-blue mb-2 group-hover:text-emerald-700 transition-colors">Feria de Ciencias e Innovación</h3>

<p class="text-slate-600 text-sm mb-4 leading-relaxed">

Investigación con enfoque en tecnología sostenible y soluciones prácticas para la comunidad.

</p>

</div>

<div class="pt-4 border-t border-emerald-200/60 flex justify-between items-center text-xs text-slate-500">

<span><i class="fa-regular fa-calendar-check mr-1"></i> Anual</span>

<span><i class="fa-solid fa-lightbulb mr-1"></i> Innovación</span>

</div>

</div>

</div>

<!-- Tarjeta 5 -->

<div class="group bg-bahai-greenbg rounded-3xl overflow-hidden border border-emerald-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-2 flex flex-col">

<div class="relative h-48 overflow-hidden">

<img src="https://images.unsplash.com/photo-1526676037777-05a232554f77?q=80&w=800&auto=format&fit=crop" alt="Deportes y Naturaleza" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">

<span class="absolute top-4 right-4 bg-bahai-blue text-bahai-gold text-xs px-3 py-1 rounded-full font-bold shadow">Bienestar</span>

</div>

<div class="p-6 flex-1 flex flex-col justify-between">

<div>

<h3 class="text-xl font-bold text-bahai-blue mb-2 group-hover:text-emerald-700 transition-colors">Deportes y Vida al Aire Libre</h3>

<p class="text-slate-600 text-sm mb-4 leading-relaxed">

Actividades físicas orientadas al trabajo en equipo, la perseverancia y el respeto al adversario.

</p>

</div>

<div class="pt-4 border-t border-emerald-200/60 flex justify-between items-center text-xs text-slate-500">

<span><i class="fa-regular fa-clock mr-1"></i> Continuo</span>

<span><i class="fa-solid fa-futbol mr-1"></i> Salud Integral</span>

</div>

</div>

</div>

<!-- Tarjeta 6 -->

<div class="group bg-bahai-greenbg rounded-3xl overflow-hidden border border-emerald-100 hover:shadow-xl transition-all duration-300 hover:-translate-y-2 flex flex-col">

<div class="relative h-48 overflow-hidden">

<img src="https://images.unsplash.com/photo-1529156069898-49953e39b3ac?q=80&w=800&auto=format&fit=crop" alt="Encuentros Juveniles" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">

<span class="absolute top-4 right-4 bg-bahai-blue text-bahai-gold text-xs px-3 py-1 rounded-full font-bold shadow">Liderazgo</span>

</div>

<div class="p-6 flex-1 flex flex-col justify-between">

<div>

<h3 class="text-xl font-bold text-bahai-blue mb-2 group-hover:text-emerald-700 transition-colors">Círculos de Diálogo Juvenil</h3>

<p class="text-slate-600 text-sm mb-4 leading-relaxed">

Espacios de debate reflexivo para desarrollar el pensamiento crítico, la elocuencia y el liderazgo ético.

</p>

</div>

<div class="pt-4 border-t border-emerald-200/60 flex justify-between items-center text-xs text-slate-500">

<span><i class="fa-regular fa-comments mr-1"></i> Bi-semanal</span>

<span><i class="fa-solid fa-comments-dollar mr-1"></i> Diálogo</span>

</div>

</div>

</div>

</div>

</div>

</section>

<!-- Sección Currículum -->

<section id="curriculum" class="py-24 bg-bahai-cream relative">

<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">

<div class="text-center max-w-3xl mx-auto mb-16">

<h2 class="text-xs font-bold uppercase tracking-widest text-emerald-700 mb-2">Formación Integral</h2>

<p class="text-3xl sm:text-4xl font-serif font-bold text-bahai-blue mb-4">Nuestro Currículum Educativo</p>

<div class="w-16 h-1 bg-bahai-gold mx-auto rounded-full mb-6"></div>

<p class="text-slate-600 leading-relaxed">

Un plan de estudios dinámico estructurado por niveles de aprendizaje moral, intelectual y espiritual para niños, prejóvenes y jóvenes.

</p>

</div>

<!-- Áreas del Currículum (5 Niveles Solicitados) -->

<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

<!-- Nivel 1: Grado 1 -->

<div class="bg-white p-8 rounded-3xl shadow-sm border border-emerald-100 hover:shadow-md transition-all flex flex-col justify-between">

<div>

<div class="flex items-center space-x-4 mb-6">

<div class="w-14 h-14 rounded-2xl bg-emerald-50 text-emerald-700 flex items-center justify-center text-2xl font-bold font-serif">

1

</div>

<div>

<h3 class="text-2xl font-bold text-bahai-blue">Grado 1</h3>

<p class="text-xs text-slate-500">Primera Infancia & Primeros Pasos</p>

</div>

</div>

<ul class="space-y-3 text-slate-600 text-sm mb-6">

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Desarrollo de Virtudes Básicas:</strong> Amor, veracidad, amabilidad y obediencia positiva.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Memorización de Frases y Canciones:</strong> Aprendizaje a través de la música y la narración oral.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Hábitos de Convivencia:</strong> Cooperación y respeto en el aula e interacción social.</span>

</li>

</ul>

</div>

<div class="pt-4 border-t border-slate-100 text-xs text-emerald-700 font-semibold flex items-center justify-between">

<span><i class="fa-solid fa-child mr-1"></i> Educación Moral Inicial</span>

<span class="bg-emerald-100 text-emerald-800 px-2.5 py-1 rounded-full">Nivel 1</span>

</div>

</div>

<!-- Nivel 2: Grado 2 -->

<div class="bg-white p-8 rounded-3xl shadow-sm border border-emerald-100 hover:shadow-md transition-all flex flex-col justify-between">

<div>

<div class="flex items-center space-x-4 mb-6">

<div class="w-14 h-14 rounded-2xl bg-teal-50 text-teal-700 flex items-center justify-center text-2xl font-bold font-serif">

2

</div>

<div>

<h3 class="text-2xl font-bold text-bahai-blue">Grado 2</h3>

<p class="text-xs text-slate-500">Construcción del Carácter</p>

</div>

</div>

<ul class="space-y-3 text-slate-600 text-sm mb-6">

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Profundización de Valores:</strong> Justicia, generosidad, limpieza y respeto mutuo.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Lectura y Comprensión Moral:</strong> Historias ilustradas con principios éticos.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Expresión Artística:</strong> Dibujo y artes manuales enfocadas en la belleza moral.</span>

</li>

</ul>

</div>

<div class="pt-4 border-t border-slate-100 text-xs text-teal-700 font-semibold flex items-center justify-between">

<span><i class="fa-solid fa-seedling mr-1"></i> Formación de Carácter</span>

<span class="bg-teal-100 text-teal-800 px-2.5 py-1 rounded-full">Nivel 2</span>

</div>

</div>

<!-- Nivel 3: Grado 3 -->

<div class="bg-white p-8 rounded-3xl shadow-sm border border-emerald-100 hover:shadow-md transition-all flex flex-col justify-between">

<div>

<div class="flex items-center space-x-4 mb-6">

<div class="w-14 h-14 rounded-2xl bg-cyan-50 text-cyan-700 flex items-center justify-center text-2xl font-bold font-serif">

3

</div>

<div>

<h3 class="text-2xl font-bold text-bahai-blue">Grado 3</h3>

<p class="text-xs text-slate-500">Conciencia y Servicio</p>

</div>

</div>

<ul class="space-y-3 text-slate-600 text-sm mb-6">

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Historia Escogida y Ejemplos de Vida:</strong> Lecciones basadas en vidas dedicadas al servicio.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Desarrollo del Pensamiento Crítico:</strong> Discernimiento moral y toma de decisiones éticas.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Primeros Proyectos de Grupo:</strong> Trabajo colaborativo para ayudar al entorno escolar.</span>

</li>

</ul>

</div>

<div class="pt-4 border-t border-slate-100 text-xs text-cyan-700 font-semibold flex items-center justify-between">

<span><i class="fa-solid fa-hands-holding-circle mr-1"></i> Orientación al Servicio</span>

<span class="bg-cyan-100 text-cyan-800 px-2.5 py-1 rounded-full">Nivel 3</span>

</div>

</div>

<!-- Nivel 4: Textos Prejuveniles -->

<div class="bg-white p-8 rounded-3xl shadow-sm border border-emerald-100 hover:shadow-md transition-all flex flex-col justify-between lg:col-span-1">

<div>

<div class="flex items-center space-x-4 mb-6">

<div class="w-14 h-14 rounded-2xl bg-amber-50 text-bahai-gold flex items-center justify-center text-2xl">

<i class="fa-solid fa-feather-pointed"></i>

</div>

<div>

<h3 class="text-2xl font-bold text-bahai-blue">Textos Prejuveniles</h3>

<p class="text-xs text-slate-500">Edades de 12 a 15 años</p>

</div>

</div>

<ul class="space-y-3 text-slate-600 text-sm mb-6">

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Empoderamiento Espiritual y Lógico:</strong> Desarrollo de la elocuencia, lenguaje y razonamiento.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Materiales Especializados:</strong> Modulos como <em>"Brisa de Confirmación"</em>, <em>"Caminando con Pasos Firmes"</em> y <em>"Pensar en las Matemáticas"</em>.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Proyectos de Servicio Comunitario:</strong> Identificación de necesidades comunitarias y ejecución de soluciones.</span>

</li>

</ul>

</div>

<div class="pt-4 border-t border-slate-100 text-xs text-amber-700 font-semibold flex items-center justify-between">

<span><i class="fa-solid fa-user-graduate mr-1"></i> Programa Prejuvenil</span>

<span class="bg-amber-100 text-amber-800 px-2.5 py-1 rounded-full">12-15 Años</span>

</div>

</div>

<!-- Nivel 5: Libros de Instituto -->

<div class="bg-white p-8 rounded-3xl shadow-sm border border-emerald-100 hover:shadow-md transition-all flex flex-col justify-between lg:col-span-2">

<div>

<div class="flex items-center space-x-4 mb-6">

<div class="w-14 h-14 rounded-2xl bg-blue-50 text-bahai-sky flex items-center justify-center text-2xl">

<i class="fa-solid fa-book-bookmark"></i>

</div>

<div>

<h3 class="text-2xl font-bold text-bahai-blue">Libros de Instituto</h3>

<p class="text-xs text-slate-500">Secundaria, Jóvenes y Adultos (Secuencia de Cursos)</p>

</div>

</div>

<div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-slate-600 text-sm mb-6">

<ul class="space-y-3">

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Reflexiones sobre la Vida del Espíritu:</strong> Estudio de pasajes sagrados y oración.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Surgir a Servir:</strong> Formación de destrezas para la enseñanza y el acompañamiento.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Enseñanza de Clases de Niños:</strong> Capacitación práctica para convertirse en educadores.</span>

</li>

</ul>

<ul class="space-y-3">

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Capacitación en Liderazgo Juvenil:</strong> Dirección de grupos de animación prejuvenil.</span>

</li>

<li class="flex items-start">

<i class="fa-solid fa-check text-bahai-gold mt-1 mr-3"></i>

<span><strong>Capacidad Organizativa y Social:</strong> Promoción de transformaciones sociales y constructivas.</span>

</li>

</ul>

</div>

</div>

<div class="pt-4 border-t border-slate-100 text-xs text-bahai-sky font-semibold flex items-center justify-between">

<span><i class="fa-solid fa-graduation-cap mr-1"></i> Instituto de Capacitación por Secuencia</span>

<span class="bg-blue-100 text-blue-800 px-2.5 py-1 rounded-full">Secundaria y Jóvenes</span>

</div>

</div>

</div>

</div>

</section>

<!-- Sección Contacto -->

<section id="contacto" class="py-24 bg-white relative">

<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">

<div class="grid grid-cols-1 lg:grid-cols-12 gap-12">

<!-- Información de Contacto -->

<div class="lg:col-span-5 flex flex-col justify-between">

<div>

<h2 class="text-xs font-bold uppercase tracking-widest text-bahai-sky mb-2">Estamos para Servirte</h2>

<p class="text-3xl sm:text-4xl font-serif font-bold text-bahai-blue mb-4">Ponte en Contacto</p>

<div class="w-16 h-1 bg-bahai-gold mb-6"></div>

<p class="text-slate-600 leading-relaxed mb-8">

¿Tienes preguntas sobre el proceso de admisión, nuestro modelo educativo o deseas agendar una visita a nuestras instalaciones? Escríbenos.

</p>

<div class="space-y-6">

<div class="flex items-start space-x-4">

<div class="w-12 h-12 rounded-2xl bg-bahai-amber text-bahai-blue flex items-center justify-center text-xl shrink-0">

<i class="fa-solid fa-location-dot"></i>

</div>

<div>

<h4 class="font-bold text-bahai-blue">Ubicación</h4>

<p class="text-sm text-slate-600">Av. Las Flores #18, Valle Verde, Ciudad de Panamá</p>

</div>

</div>

<div class="flex items-start space-x-4">

<div class="w-12 h-12 rounded-2xl bg-bahai-amber text-bahai-blue flex items-center justify-center text-xl shrink-0">

<i class="fa-solid fa-envelope"></i>

</div>

<div>

<h4 class="font-bold text-bahai-blue">Correo Electrónico</h4>

<p class="text-sm text-slate-600">contacto@escuelabahai.edu</p>

</div>

</div>

<div class="flex items-start space-x-4">

<div class="w-12 h-12 rounded-2xl bg-bahai-amber text-bahai-blue flex items-center justify-center text-xl shrink-0">

<i class="fa-solid fa-phone"></i>

</div>

<div>

<h4 class="font-bold text-bahai-blue">Teléfono</h4>

<p class="text-sm text-slate-600">+507 234-5678 / +507 6000-0000</p>

</div>

</div>

</div>

</div>

<div class="mt-12 p-6 rounded-2xl bg-bahai-blue text-white relative overflow-hidden">

<i class="fa-solid fa-quote-right absolute -bottom-4 -right-4 text-7xl text-white/10"></i>

<p class="text-sm italic text-slate-200">

"La luz de un mundo bueno y justo depende de la educación que brindamos a nuestros niños hoy."

</p>

</div>

</div>

<!-- Formulario -->

<div class="lg:col-span-7">

<div class="bg-white p-8 sm:p-10 rounded-3xl border border-emerald-100 shadow-lg relative">

<!-- Mensaje de confirmación (oculto por defecto) -->

<div id="form-success" class="hidden mb-6 p-4 rounded-2xl bg-emerald-100 border border-emerald-300 text-emerald-800 text-sm flex items-center space-x-3">

<i class="fa-solid fa-circle-check text-xl"></i>

<span>¡Gracias por escribirnos! Tu mensaje ha sido enviado con éxito. Te responderemos pronto.</span>

</div>

<form id="contact-form" onsubmit="handleFormSubmit(event)" class="space-y-6">

<div>

<label for="nombre" class="block text-sm font-semibold text-slate-700 mb-2">Nombre Completo</label>

<input type="text" id="nombre" required placeholder="Ej. María González" class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-emerald-600 focus:border-transparent outline-none transition-all bg-bahai-cream text-slate-800">

</div>

<div>

<label for="correo" class="block text-sm font-semibold text-slate-700 mb-2">Correo Electrónico</label>

<input type="email" id="correo" required placeholder="ejemplo@correo.com" class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-emerald-600 focus:border-transparent outline-none transition-all bg-bahai-cream text-slate-800">

</div>

<div>

<label for="asunto" class="block text-sm font-semibold text-slate-700 mb-2">Asunto</label>

<select id="asunto" class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-emerald-600 focus:border-transparent outline-none transition-all bg-bahai-cream text-slate-800">

<option value="admision">Información de Admisión</option>

<option value="actividades">Consulta de Actividades</option>

<option value="visita">Agendar Visita</option>

<option value="otro">Otro Asunto</option>

</select>

</div>

<div>

<label for="mensaje" class="block text-sm font-semibold text-slate-700 mb-2">Mensaje</label>

<textarea id="mensaje" rows="4" required placeholder="Escribe tu mensaje aquí..." class="w-full px-4 py-3 rounded-xl border border-slate-300 focus:ring-2 focus:ring-emerald-600 focus:border-transparent outline-none transition-all bg-bahai-cream text-slate-800 resize-none"></textarea>

</div>

<button type="submit" class="w-full py-4 rounded-xl bg-bahai-blue text-white font-bold text-base hover:bg-emerald-800 shadow-md hover:shadow-lg transition-all transform hover:-translate-y-0.5 flex items-center justify-center space-x-2">

<i class="fa-solid fa-paper-plane"></i>

<span>Enviar Mensaje</span>

</button>

</form>

</div>

</div>

</div>

</div>

</section>

<!-- Pie de página (Footer) -->

<footer class="bg-bahai-blue text-white pt-16 pb-8">

<div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">

<div class="grid grid-cols-1 md:grid-cols-4 gap-8 pb-12 border-b border-white/10">

<div class="md:col-span-2">

<div class="flex items-center space-x-3 mb-4">

<div class="w-10 h-10 rounded-full bg-bahai-gold flex items-center justify-center text-bahai-blue font-serif font-bold text-lg">9</div>

<span class="font-serif text-2xl font-bold">Escuela Bahá'í</span>

</div>

<p class="text-slate-300 text-sm leading-relaxed max-w-md">

Dedicados a formar generaciones conscientes de la unidad humana, con mentes abiertas al saber y corazones orientados al servicio desinteresado.

</p>

</div>

<div>

<h4 class="text-bahai-gold font-bold mb-4">Navegación</h4>

<ul class="space-y-2 text-sm text-slate-300">

<li><a href="#inicio" class="hover:text-white transition-colors">Inicio</a></li>

<li><a href="#actividades" class="hover:text-white transition-colors">Actividades</a></li>

<li><a href="#curriculum" class="hover:text-white transition-colors">Currículum</a></li>

<li><a href="#contacto" class="hover:text-white transition-colors">Contacto</a></li>

</ul>

</div>

<div>

<h4 class="text-bahai-gold font-bold mb-4">Síguenos</h4>

<div class="flex space-x-4">

<a href="#" class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-bahai-gold hover:text-bahai-blue transition-colors"><i class="fa-brands fa-facebook-f"></i></a>

<a href="#" class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-bahai-gold hover:text-bahai-blue transition-colors"><i class="fa-brands fa-instagram"></i></a>

<a href="#" class="w-10 h-10 rounded-full bg-white/10 flex items-center justify-center hover:bg-bahai-gold hover:text-bahai-blue transition-colors"><i class="fa-brands fa-youtube"></i></a>

</div>

</div>

</div>

<div class="pt-8 text-center text-xs text-slate-400">

<p>&copy; 2026 Escuela Bahá'í. Todos los derechos reservados. Basado en principios de unidad y servicio.</p>

</div>

</div>

</footer>

<!-- Lógica de Interacción JavaScript -->

<script>

// Manejo del Menú Móvil

const menuBtn = document.getElementById('mobile-menu-btn');

const mobileMenu = document.getElementById('mobile-menu');

const menuIcon = document.getElementById('menu-icon');

const mobileLinks = document.querySelectorAll('.mobile-link');

menuBtn.addEventListener('click', () => {

const isHidden = mobileMenu.classList.contains('hidden');

if (isHidden) {

mobileMenu.classList.remove('hidden');

menuIcon.classList.remove('fa-bars');

menuIcon.classList.add('fa-xmark');

} else {

mobileMenu.classList.add('hidden');

menuIcon.classList.remove('fa-xmark');

menuIcon.classList.add('fa-bars');

}

});

// Cerrar menú móvil al hacer clic en un enlace

mobileLinks.forEach(link => {

link.addEventListener('click', () => {

mobileMenu.classList.add('hidden');

menuIcon.classList.remove('fa-xmark');

menuIcon.classList.add('fa-bars');

});

});

// Manejo del Envío del Formulario

function handleFormSubmit(event) {

event.preventDefault();

const successMsg = document.getElementById('form-success');

const form = document.getElementById('contact-form');

// Mostrar mensaje de éxito

successMsg.classList.remove('hidden');

form.reset();

// Desplazar suavemente hacia el mensaje

successMsg.scrollIntoView({ behavior: 'smooth', block: 'center' });

// Ocultar mensaje tras 6 segundos

setTimeout(() => {

successMsg.classList.add('hidden');

}, 6000);

}

// Efecto Sombra en Navegación al Hacer Scroll

window.addEventListener('scroll', () => {

const header = document.getElementById('main-header');

if (window.scrollY > 20) {

header.classList.add('shadow-md');

} else {

header.classList.remove('shadow-md');

}

});

</script>

</body>

</html>
