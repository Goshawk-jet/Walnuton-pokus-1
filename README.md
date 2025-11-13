<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Walnuton - Řemeslné Dřevěné Výrobky</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans text-gray-900 bg-white">

  <!-- Hero sekce -->
  <section class="relative h-screen bg-cover bg-center" style="background-image: url('images/drevo.jpg');">
    <div class="absolute inset-0 bg-black bg-opacity-60"></div>
    <header class="absolute top-0 left-0 w-full flex justify-between items-center p-6 text-white z-10">
      <h1 class="text-lg font-semibold">Walnuton</h1>
      <nav class="space-x-6 font-medium">
        <a href="#" class="hover:text-yellow-400">Úvod</a>
        <a href="#produkty" class="hover:text-yellow-400">Produkty</a>
        <a href="#omne" class="hover:text-yellow-400">O mně</a>
      </nav>
    </header>

    <div class="relative z-10 flex flex-col justify-center h-full px-10 md:px-20 text-white">
      <h2 class="text-6xl md:text-7xl font-extrabold leading-tight mb-4">
        Řemeslné <br> Dřevěné <br> Výrobky
      </h2>
      <p class="text-xl mb-8">Ručně vyráběné s láskou a precizností</p>
      <a href="#produkty" class="bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-3 px-6 rounded-lg w-max">
        Prohlédnout produkty
      </a>
    </div>
  </section>

  <!-- Produkty -->
  <section id="produkty" class="py-20 bg-gray-50">
    <div class="max-w-6xl mx-auto px-6 grid md:grid-cols-3 gap-10">
      
      <!-- Misky -->
      <div class="bg-white shadow-lg rounded-2xl overflow-hidden hover:-translate-y-2 transition">
        <img src="images/misky.jpg" alt="Dřevěné misky" class="w-full h-80 object-cover">
        <div class="p-6 text-center">
          <h3 class="text-2xl font-bold text-gray-800 mb-2">Dřevěné misky</h3>
          <p class="text-gray-600 mb-6">Soustružené a řezbované misky z kvalitního dřeva</p>
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-2 px-6 rounded-lg">Zobrazit více</button>
        </div>
      </div>

      <!-- Prkénka -->
      <div class="bg-white shadow-lg rounded-2xl overflow-hidden hover:-translate-y-2 transition">
        <img src="images/prkenka.jpg" alt="Kuchyňská prkénka" class="w-full h-80 object-cover">
        <div class="p-6 text-center">
          <h3 class="text-2xl font-bold text-gray-800 mb-2">Kuchyňská prkénka</h3>
          <p class="text-gray-600 mb-6">Robustní prkénko pro každodenní použití</p>
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-2 px-6 rounded-lg">Zobrazit více</button>
        </div>
      </div>

      <!-- Řezby -->
      <div class="bg-white shadow-lg rounded-2xl overflow-hidden hover:-translate-y-2 transition">
        <img src="images/rezby.jpg" alt="Dekorativní řezby" class="w-full h-80 object-cover">
        <div class="p-6 text-center">
          <h3 class="text-2xl font-bold text-gray-800 mb-2">Dekorativní řezby</h3>
          <p class="text-gray-600 mb-6">Umělecké dřevěné řezby ručně vyrobené</p>
          <button class="bg-yellow-500 hover:bg-yellow-600 text-black font-semibold py-2 px-6 rounded-lg">Zobrazit více</button>
        </div>
      </div>

    </div>
  </section>

  <!-- O mně -->
  <section id="omne" class="py-20">
    <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center gap-10 px-6">
      <div class="md:w-1/2">
        <img src="images/rezbar.jpg" alt="Řezbář při práci" class="rounded-2xl shadow-lg">
      </div>
      <div class="md:w-1/2">
        <h4 class="uppercase tracking-wide text-gray-500 font-semibold mb-2">Walnuton</h4>
        <h2 class="text-4xl font-bold text-gray-800 mb-4">Ruční Práce a Tradice</h2>
        <p class="text-gray-700 leading-relaxed mb-4">
          Každý výrobek je vytvořen s péčí a pozorností k detailu. Používáme tradiční techniky řezbářství a moderní zpracování dřeva.
        </p>
        <p class="text-gray-700 leading-relaxed">
          Naše produkty jsou vyrobeny z lokálního dřeva nejvyšší kvality, které je pečlivě vybráno a zpracováno.
        </p>
      </div>
    </div>
  </section>

</body>
</html>
