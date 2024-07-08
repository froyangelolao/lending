<template>
    <div class="bg-gray-900 text-white">
      <header class="py-7 px-12 flex justify-between items-center">
        <div>
          <img src="../img/Lending_logo.png" alt="LendCash Logo" class="object-cover h-20 w-15" />
        </div>
        <nav>
          <ul class="flex space-x-11">
            <li><a href="/" class="hover:underline">Home</a></li>
            <li><a href="/offer" class="hover:underline">Offer</a></li>
            <li><a href="/about" class="hover:underline">About</a></li>
            <li><a href="/subscription" class="hover:underline">Subscription</a></li>
            <li><button class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-4 rounded">Apply Here</button></li>
          </ul>
        </nav>
      </header>
      <main class="container mx-auto px-4 py-5 text-center">
        <h1 class="text-4xl font-bold mb-4">ERD Financial Solution</h1>
        <h2 class="text-2xl mb-2">An Online Microfinance lending System</h2>
        <h3 class="text-3xl font-bold mb-8">Creating Opportunities, One Microloan at a Time</h3>
        <div>

            <h1 class="text-4xl font-bold mb-4">LendCash Offers</h1>
            
        </div>
        <section class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <div class="bg-gray-800 p-6 rounded shadow">
            <img src="../img/grouping.png" alt="grouping" class="mx-auto w-40 max-w-md h-auto" />
            <h4 class="text-xl font-bold mb-4">Group Lending</h4>
            <p class="text-justify">Offers small groups of individuals come together to access financial services. In this system, members guarantee each other's loans, fostering a sense of shared responsibility and mutual support. By empowering communities and encouraging cooperation, group lending helps create sustainable economic opportunities and drives financial inclusion for underserved populations.</p>
          </div>
          <div class="bg-gray-800 p-6 rounded shadow">
            <img src="../img/surcharge.png" alt="surcharge" class="mx-auto w-40 max-w-md h-auto" />
            <h4 class="text-xl font-bold mb-4">NO Surcharge</h4>
            <p class="text-justify">Providing loans and financial services without additional fees beyond the agreed interest rates. This approach ensures that borrowers are not burdened with hidden costs or extra charges, making financial products more transparent and accessible. By eliminating surcharges, microfinance institutions can foster trust and support financial inclusion, helping individuals and small businesses to thrive without the worry of unexpected expenses.</p>
          </div>
          <div class="bg-gray-800 p-6 rounded shadow">
            <img src="../img/collateral.png" alt="collateral" class="mx-auto w-40 max-w-md h-auto" />
            <h4 class="text-xl font-bold mb-4">NO Collateral</h4>
            <p class="text-justify">Providing loans and financial services without requiring borrowers to pledge assets as security. This approach enables individuals, particularly those with limited or no assets, to access credit and other financial services. By removing the barrier of collateral, microfinance institutions empower underserved populations, fostering entrepreneurship and economic growth while promoting financial inclusion and resilience.</p>
          </div>
        </section>
  
        <section class="mt-16">
          <h2 class="text-3xl font-bold mb-8">LendCash Microfinance System for ERD Financial Solution</h2>
          <p class="text-lg mb-4">Providing financial servicing to people who are not eligible of banking loans and related loan services. This targets individuals and small businesses by offering affordable financial products. Microfinance institutions empower low-income individuals to start or expand businesses, improve their livelihoods, and achieve financial independence.</p>
          <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mt-8">
            <div class="flex flex-col items-center justify-center">
              <img src="" alt="Easy Loan Process" class="h-24 mb-4" />
              <h5 class="text-xl font-bold">Easy loan process</h5>
            </div>
            <div class="flex flex-col items-center justify-center">
              <img src="" alt="Quick Cash Disbursement" class="h-24 mb-4" />
              <h5 class="text-xl font-bold">Quick Cash disbursement</h5>
            </div>
            <div class="flex flex-col items-center justify-center">
              <img src="" alt="Hassle Free Requirements" class="h-24 mb-4" />
              <h5 class="text-xl font-bold">Hassle free requirements</h5>
            </div>
          </div>
        </section>
      </main>
      <footer class="bg-gray-800 py-4 px-6 text-center">
        <p>&copy; 2023 LendCash. All rights reserved.</p>
      </footer>
    </div>
  </template>
  
  <script setup>
  
  </script>