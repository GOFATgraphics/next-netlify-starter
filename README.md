<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GOFAT COUTURE - Clothing Samples</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100">

  <!-- Header Section -->
  <header class="bg-blue-500 text-white text-center py-6">
    <h1 class="text-4xl font-bold">GOFAT COUTURE</h1>
    <p class="mt-2">Elegant and Custom Tailoring Services</p>
    <!-- Navigation -->
    <nav class="mt-4">
      <a href="index.html" class="text-white mx-4">Home</a>
      <a href="samples.html" class="text-white mx-4">Clothing Samples</a>
    </nav>
  </header>

  <!-- Main Content -->
  <main class="container mx-auto mt-8">
    <h2 class="text-3xl font-bold text-center mb-6">Clothing Samples</h2>

    <!-- Sample Clothing Gallery -->
    <section class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
      <!-- Sample Item 1 -->
      <div class="bg-white p-4 rounded shadow-md">
        <img src="https://source.unsplash.com/400x400?clothes,formal" alt="Sample Outfit 1" class="w-full rounded mb-4">
        <h3 class="text-lg font-bold mb-2">Classic Suit</h3>
        <p>A tailored classic suit perfect for formal events.</p>
      </div>

      <!-- Sample Item 2 -->
      <div class="bg-white p-4 rounded shadow-md">
        <img src="https://source.unsplash.com/400x400?clothes,dress" alt="Sample Outfit 2" class="w-full rounded mb-4">
        <h3 class="text-lg font-bold mb-2">Elegant Dress</h3>
        <p>An elegant dress for special occasions, tailored to perfection.</p>
      </div>

      <!-- Sample Item 3 -->
      <div class="bg-white p-4 rounded shadow-md">
        <img src="https://source.unsplash.com/400x400?clothes,casual" alt="Sample Outfit 3" class="w-full rounded mb-4">
        <h3 class="text-lg font-bold mb-2">Casual Attire</h3>
        <p>Comfortable yet stylish casual wear.</p>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="text-center py-4 mt-8 text-gray-500">
    <p>&copy; 2024 GOFAT COUTURE. All rights reserved.</p>
  </footer>

</body>
</html>
# Next + Netlify Starter

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GOFAT COUTURE</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100">

  <!-- Header Section -->
  <header class="bg-blue-500 text-white text-center py-6">
    <h1 class="text-4xl font-bold">GOFAT COUTURE</h1>
    <p class="mt-2">Elegant and Custom Tailoring Services</p>
    <!-- Navigation -->
    <nav class="mt-4">
      <a href="index.html" class="text-white mx-4">Home</a>
      <a href="samples.html" class="text-white mx-4">Clothing Samples</a>
    </nav>
  </header>

  <!-- Main Content -->
  <main class="container mx-auto mt-8">

    <!-- Profile Section -->
    <section class="bg-white p-6 rounded shadow-md mb-8">
      <h2 class="text-2xl font-bold mb-4">About GOFAT COUTURE</h2>
      <p>Welcome to GOFAT COUTURE! We specialize in creating tailor-made, custom-fitted clothing for individuals who appreciate the art of fine tailoring. Our years of experience in the fashion industry have allowed us to deliver premium quality suits, dresses, and more, all crafted to your unique measurements.</p>
    </section>

    <!-- Measurement Form Section -->
    <section class="text-center">
      <h2 class="text-2xl font-bold mb-4">Take Your Measurements</h2>
      <p class="mb-6">Fill out the form below with your body measurements for your custom tailored outfit.</p>

      <!-- Measurement Form -->
      <form id="measurement-form" class="bg-white p-6 rounded shadow-md mx-auto max-w-lg">
        <!-- Name -->
        <div class="mb-4">
          <label class="block text-gray-700" for="name">Full Name</label>
          <input class="w-full p-2 border border-gray-300 rounded" type="text" id="name" name="name" required>
        </div>

        <!-- Email -->
        <div class="mb-4">
          <label class="block text-gray-700" for="email">Email</label>
          <input class="w-full p-2 border border-gray-300 rounded" type="email" id="email" name="email" required>
        </div>

        <!-- Shoulder -->
        <div class="mb-4">
          <label class="block text-gray-700" for="shoulder">Shoulder (cm)</label>
          <input class="w-full p-2 border border-gray-300 rounded" type="number" id="shoulder" name="shoulder" required>
        </div>

        <!-- Sleeve Length -->
        <div class="mb-4">
          <label class="block text-gray-700" for="sleeve">Sleeve Length (cm)</label>
          <input class="w-full p-2 border border-gray-300 rounded" type="number" id="sleeve" name="sleeve" required>
        </div>

        <!-- Top Length -->
        <div class="mb-4">
          <label class="block text-gray-700" for="top-length">Top Length (cm)</label>
          <input class="w-full p-2 border border-gray-300 rounded" type="number" id="top-length" name="top-length" required>
        </div>

        <!-- Trouser Length -->
        <div class="mb-4">
          <label class="block text-gray-700" for="trouser">Trouser Length (cm)</label>
          <input class="w-full p-2 border border-gray-300 rounded" type="number" id="trouser" name="trouser" required>
        </div>

        <!-- Neck Size -->
        <div class="mb-4">
          <label class="block text-gray-700" for="neck">Neck (cm)</label>
          <input class="w-full p-2 border border-gray-300 rounded" type="number" id="neck" name="neck" required>
        </div>

        <!-- Chest Size -->
        <div class="mb-4">
          <label class="block text-gray-700" for="chest">Chest (cm)</label>
          <input class="w-full p-2 border border-gray-300 rounded" type="number" id="chest" name="chest" required>
        </div>

        <!-- Thigh Size -->
        <div class="mb-4">
          <label class="block text-gray-700" for="thigh">Thigh (cm)</label>
          <input class="w-full p-2 border border-gray-300 rounded" type="number" id="thigh" name="thigh" required>
        </div>

        <!-- Submit Button -->
        <div class="mt-6">
          <button type="submit" class="w-full bg-blue-500 text-white py-2 rounded">Submit Measurements</button>
        </div>
      </form>
    </section>
  </main>

  <!-- Footer -->
  <footer class="text-center py-4 mt-8 text-gray-500">
    <p>&copy; 2024 GOFAT COUTURE. All rights reserved.</p>
  </footer>

  <script>
    document.getElementById('measurement-form').addEventListener('submit', function(e) {
      e.preventDefault();
      alert('Measurements submitted successfully!');
    });
  </script>
</body>
</html>
[
