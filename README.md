<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Elaiyavan – Digital Card</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 flex items-center justify-center h-screen">
  <div class="bg-white p-6 rounded-2xl shadow-xl text-center w-80">
    <img src="ennoda.JPG" class="w-24 h-24 mx-auto rounded-full mb-4" alt="Profile">
    <h1 class="text-xl font-semibold">Elaiyavan K</h1>
    <p class="text-gray-600">Graphic Designer @ ArtiePoster</p>

    <a href="elaiyavan.vcf" download class="block mt-4 bg-indigo-600 text-white px-4 py-2 rounded-xl">
      Download Contact
    </a>

    <canvas id="qrcode" class="mt-6 mx-auto"></canvas>

    <div class="mt-4 space-x-4 text-2xl">
      <a href="https://instagram.com/elxiyxvxn">📷</a>
      <a href="mailto:hello@artieposter.in">✉️</a>
    </div>
  </div>

  <script src="https://hihello.com/p/0fd33e69-ce97-48a4-ae51-9a42b1fe8c64"></script>
  <script>
    QRCode.toCanvas(document.getElementById('qrcode'), window.location.href);
  </script>
</body>
</html>
