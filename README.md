<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GolfHub</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(135deg, #000000, #006400);
      color: white;
      font-family: 'Arial', sans-serif;
    }
    .fade-in {
      animation: fadeIn 2s ease-in;
    }
    .gallery img {
      transition: transform 0.3s ease-in-out;
    }
    .gallery img:hover {
      transform: scale(1.1);
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body class="text-gray-100">

  <!-- Header -->
  <header class="text-center py-8 fade-in">
    <img src="img/header.jpg.jpg" alt="Golfer Swing" class="w-full h-80 object-cover rounded-b-2xl">
    <h1 class="text-4xl font-bold mt-6">GolfHub - Where Beginners Become Pros & Pros Become Legends</h1>
    <p class="text-xl mt-2">Join the club that's trained champions for decades. Whether you're picking up a club for the first
      time or perfecting your competitive edge, GolfHub will take your game to the next level.
    </p>
  </header>

  <!-- About Section -->
  <section class="text-center py-10 max-w-4xl mx-auto px-4">
    <img src="img/coach.jpg.jpg" alt="Coach Augustine" class="w-40 h-40 rounded-full mx-auto mb-6 border-4 border-green-500">
    <p class="text-lg leading-relaxed">
      With over three decades of experience, Augustine has coached hundreds of golfers, from beginners to professionals. 
      His unique approach combines skill, patience, and passion to bring out the best in every player.
    </p>
  </section>

  <!-- Testimonials -->
  <section class="py-10 bg-green-900 bg-opacity-70 text-center">
    <h2 class="text-3xl font-bold mb-6">What Students Say</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-6xl mx-auto px-4">
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <p>"Coach Augustine transformed my game! From slicing every shot to hitting straight drives!"</p>
        <p class="mt-4 font-semibold">- Amud.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <p>"30 years of experience shows. Augustine knows exactly how to fix your swing."</p>
        <p class="mt-4 font-semibold">- Mike K.</p>
      </div>
       <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <p>"Patient, skilled, and fun to learn from. Best golf coach out there!"</p>
        <p class="mt-4 font-semibold">- Sarah W.</p>
      </div>
    </div>
  </section>

  <!-- Gallery -->
  <section class="py-10 text-center">
    <h2 class="text-3xl font-bold mb-6">Gallery</h2>
    <div class="gallery grid grid-cols-2 md:grid-cols-4 gap-4 max-w-6xl mx-auto px-4">
      <img src="img/student1.jpg.jpg" alt="Student 1" class="rounded-lg shadow-lg">
      <img src="img/student2.jpg.jpg" alt="Student 2" class="rounded-lg shadow-lg">
      <img src="img/student3.jpg.jpg" alt="Student 3" class="rounded-lg shadow-lg">
      <img src="img/student4.jpg.jpg" alt="Student 4" class="rounded-lg shadow-lg">
    </div>
  </section>

  <!-- Lessons & Pricing -->
  <section class="py-10 bg-green-800 text-center">
    <h2 class="text-3xl font-bold mb-6">Lessons & Pricing</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 max-w-6xl mx-auto px-4">
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <h3 class="text-xl font-bold mb-4">Beginner Package</h3>
        <p>$100 / session</p>
        <p class="mt-2">Perfect for new golfers starting their journey.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <h3 class="text-xl font-bold mb-4">Intermediate Package</h3>
        <p>$150 / session</p>
        <p class="mt-2">For golfers looking to improve their game.</p>
      </div>
      <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
        <h3 class="text-xl font-bold mb-4">Pro Package</h3>
        <p>$250 / session</p>
        <p class="mt-2">Advanced training for serious golfers.</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section class="py-10 text-center">
    <h2 class="text-3xl font-bold mb-6">Contact Me</h2>
    <p class="mb-4">Phone: +260 97 000 0000 | Email: mpundurichard472@gmail.com | Instagram | What's up</p>
    <button class="bg-green-500 hover:bg-green-600 text-black font-bold py-2 px-6 rounded-full">
      <a href="https://forms.gle/jzqUtujLcnEhVbzc9" target="_blank" class="book-btn">Unlock Your Inner Pro - Book Now</a>
    </button>
  </section>

</body>
</html>
