<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Plants for Sale - Alcovy Natives</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body { 
      font-family: 'Arial', sans-serif; 
      background-color: #2F4F2F; /* Forest green background */
    }
    .bg-forest-green { background-color: #2F4F2F; }
    .border-red { border-color: #FF0000; }
    .text-red { color: #FF0000; }
    .hover\:bg-red:hover { background-color: #FF0000; }
    .hover\:text-red:hover { color: #FF0000; }
  </style>
</head>
<body>
  <!-- Header -->
  <header class="bg-forest-green text-white sticky top-0 z-50 border-b-2 border-red">
    <div class="container mx-auto flex justify-between items-center p-4">
      <div class="flex items-center">
        <img src="images/logo.png" alt="Alcovy Natives Logo" class="h-12 mr-4">
        <h1 class="text-2xl font-bold">Alcovy Natives</h1>
      </div>
      <nav>
        <ul class="flex space-x-6">
          <li><a href="index.html" class="hover:text-red">Home</a></li>
          <li><a href="#about" class="hover:text-red">About</a></li>
          <li><a href="plants.html" class="hover:text-red">Plants</a></li>
          <li><a href="#calendar" class="hover:text-red">Calendar</a></li>
          <li><a href="#contact" class="hover:text-red">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Plants Section -->
  <section class="py-12 bg-white">
    <div class="container mx-auto">
      <h2 class="text-3xl font-bold text-center mb-8">Plants for Sale</h2>
      <p class="text-lg text-center mb-8">Discover our native Georgia plants, perfect for sustainable gardens!</p>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
        <!-- Plant 1: Black-eyed Susan -->
        <div class="bg-gray-50 p-6 rounded shadow hover:shadow-lg border-2 border-red">
          <!-- Image downloaded from NC State (with permission) and hosted locally -->
          <!-- Original URL: https://plants.ces.ncsu.edu/media/images/Rudbeckia_hirta_001.jpg -->
          <img src="images/rudbeckia_hirta.jpg" alt="Black-eyed Susan" class="w-full h-48 object-cover rounded mb-4 border-2 border-red">
          <h3 class="text-xl font-semibold mb-2">Black-eyed Susan</h3>
          <p class="text-gray-600 mb-4">Bright yellow daisy-like flowers, ideal for pollinator gardens.</p>
          <a href="plant-detail.html" class="bg-forest-green text-white px-4 py-2 rounded border-2 border-red hover:bg-red">View Details</a>
        </div>
        <!-- Plant 2: Swamp Milkweed -->
        <div class="bg-gray-50 p-6 rounded shadow hover:shadow-lg border-2 border-red">
          <!-- Image downloaded from NC State (with permission) and hosted locally -->
          <!-- Original URL: https://plants.ces.ncsu.edu/media/images/Asclepias_incarnata_002.jpg -->
          <img src="images/asclepias_incarnata.jpg" alt="Swamp Milkweed" class="w-full h-48 object-cover rounded mb-4 border-2 border-red">
          <h3 class="text-xl font-semibold mb-2">Swamp Milkweed</h3>
          <p class="text-gray-600 mb-4">Pink blooms that support monarch butterflies.</p>
          <a href="plant-detail.html" class="bg-forest-green text-white px-4 py-2 rounded border-2 border-red hover:bg-red">View Details</a>
        </div>
        <!-- Plant 3: Georgia Aster -->
        <div class="bg-gray-50 p-6 rounded shadow hover:shadow-lg border-2 border-red">
          <!-- Image downloaded from NC State (with permission) and hosted locally -->
          <!-- Original URL: https://plants.ces.ncsu.edu/media/images/Symphyotrichum_georgianum_001.jpg -->
          <img src="images/symphyotrichum_georgianum.jpg" alt="Georgia Aster" class="w-full h-48 object-cover rounded mb-4 border-2 border-red">
          <h3 class="text-xl font-semibold mb-2">Georgia Aster</h3>
          <p class="text-gray-600 mb-4">Purple fall blooms for late-season color.</p>
          <a href="plant-detail.html" class="bg-forest-green text-white px-4 py-2 rounded border-2 border-red hover:bg-red">View Details</a>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-forest-green text-white p-6 border-t-2 border-red">
    <div class="container mx-auto text-center">
      <p class="mb-2">Alcovy Natives | 123 Main St, Your City, GA 12345</p>
      <p class="mb-2">Email: info@alcovynatives.org | Phone: (123) 456-7890</p>
      <div class="flex justify-center space-x-4 mb-2">
        <a href="#" class="hover:text-red">Facebook</a>
        <a href="#" class="hover:text-red">Twitter</a>
        <a href="#" class="hover:text-red">Instagram</a>
      </div>
      <p>Accredited by Cognia | Images courtesy of NC State Extension Plants Database</p>
    </div>
  </footer>

  <script>
    // Smooth scrolling for navigation links
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
          behavior: 'smooth'
        });
      });
    });
  </script>
</body>
</html>
