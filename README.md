# coursera-test
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Harrys First Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: lightblue;
    }

    header {
      text-align: center;
      padding: 20px;
    }

    main {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }

    #mason {
      align: center;
      box-sizing: border-box;
      margin: 40px;
      background-color: yellow;
      border: 5px solid black;
      padding: 10px;
      hover: red;
    }
    

    #fish-gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .fish-image {
      width: 200px;
      height: 200px;
      object-fit: cover;
      margin: 10px;
    }

    #fish-facts {
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header #mason>
    <h1>Mason is a Great Dog</h1>
  </header>
  <main>
    <h2>London is Blue</h2>
    <section id="great dog">
      </section>
    <section id="blue london">
      <h2>Fun facts</h2>
      <ul>
        <li>Did you know that goldfish have a memory span of 3 seconds?</li>
        <li>Sharks can detect one drop of blood in a million gallons of water.</li>
      </ul>
    </section>
  </main>
  <footer>
    <p>&copy; 2024 Fishy Business</p>
  </footer>
  <script>
    const fishGallery = document.getElementById('fish-gallery');

    // Array of fish image URLs
    const fishImages = [
      'image1.jpg',
      'image2.jpg',
      'image3.jpg'
    ];

    // Function to create fish image elements
    function createFishImage(url) {
      const img = document.createElement('img');
      img.classList.add('fish-image');
      img.src = url;
      return img;
    }

    // Add fish images to the gallery
    fishImages.forEach(url => {
      fishGallery.appendChild(createFishImage(url));
    });
  </script>
</body>
</html>






