<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Église Centre d’adoration source de vie (siloé) </title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans bg-gray-50 text-gray-800">

  <!-- Barre de navigation -->
  <header class="bg-indigo-800 text-white shadow-lg">
    <div class="max-w-7xl mx-auto flex justify-between items-center p-4">
      <h1 class="text-2xl font-bold">Église Centre d’adoration source de vie (siloé) </h1>
      <nav class="space-x-6">
        <a href="#accueil" class="hover:text-yellow-300">Accueil</a>
        <a href="#apropos" class="hover:text-yellow-300">À Propos</a>
        <a href="#cultes" class="hover:text-yellow-300">Cultes</a>
        <a href="#evenements" class="hover:text-yellow-300">Événements</a>
        <a href="#contact" class="hover:text-yellow-300">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero section -->
  <section id="accueil" class="relative bg-cover bg-center h-[500px]" style="background-image: url('siloe.jpg' );">
    <div class="absolute inset-0 bg-black bg-opacity-50 flex flex-col justify-center items-center text-center text-white">
      <h2 class="text-4xl md:text-6xl font-bold mb-4">Bienvenue dans notre église</h2>
      <p class="text-lg md:text-2xl mb-6">Un lieu de foi, de partage et d’amour</p>
      <a href="#cultes" class="bg-yellow-400 hover:bg-yellow-500 text-black font-semibold py-3 px-6 rounded-lg shadow-lg">
        Rejoignez-nous
      </a>
    </div>
  </section>

  <!-- Section À propos -->
  <section id="apropos" class="max-w-6xl mx-auto py-16 px-6">
    <h3 class="text-3xl font-bold text-center mb-8 text-indigo-800">À Propos de Nous</h3>
    <p class="text-lg text-center leading-relaxed">
      Fondée en 1995, l’Église Lumière du Monde a pour mission de guider les âmes dans la foi chrétienne, 
      d’offrir un espace de prière et d’accompagnement spirituel, et de bâtir une communauté unie 
      dans l’amour et la fraternité.
    </p>
  </section>

  <!-- Section Cultes -->
  <section id="cultes" class="bg-indigo-50 py-16">
    <div class="max-w-6xl mx-auto px-6">
      <h3 class="text-3xl font-bold text-center mb-10 text-indigo-800">Nos Cultes</h3>
      <div class="grid md:grid-cols-3 gap-8 text-center">
        <div class="bg-white p-6 rounded-2xl shadow-lg hover:shadow-2xl transition">
          <h4 class="text-xl font-semibold mb-4">Culte du Dimanche</h4>
          <p class="text-gray-600">Chaque dimanche à 9h00</p>
        </div>
        <div class="bg-white p-6 rounded-2xl shadow-lg hover:shadow-2xl transition">
          <h4 class="text-xl font-semibold mb-4">Étude Biblique</h4>
          <p class="text-gray-600">Mardi à 16h00</p>
        </div>
        <div class="bg-white p-6 rounded-2xl shadow-lg hover:shadow-2xl transition">
          <h4 class="text-xl font-semibold mb-4">Prière des malades</h4>
          <p class="text-gray-600">Vendredi à 17h00</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Section Événements -->
  <section id="evenements" class="max-w-6xl mx-auto py-16 px-6">
    <h3 class="text-3xl font-bold text-center mb-10 text-indigo-800">Événements à venir</h3>
    <div class="grid md:grid-cols-2 gap-8">
      <div class="bg-white p-6 rounded-2xl shadow-lg">
        <h4 class="text-xl font-semibold mb-2">Séminaires des jeunes</h4>
        <p class="text-gray-600">Du 6 au 10 août 2025</p>
      </div>
    </div>
  </section>

  <!-- Section Contact -->
  <section id="contact" class="bg-indigo-800 text-white py-16">
    <div class="max-w-6xl mx-auto px-6 text-center">
      <h3 class="text-3xl font-bold mb-6">Contactez-nous</h3>
      <p>Téléphone : +242 06 4738695</p>
      <p>Adresse : Arret carrefour, Makabandilou, Brazzaville</p>
    </div>
  </section>

  <!-- Pied de page -->
  <footer class="bg-gray-900 text-gray-300 text-center py-6">
    &copy; 2025 Église Centre d’adoration source de vie (siloé)  - Tous droits réservés
  </footer>

</body>
</html>
