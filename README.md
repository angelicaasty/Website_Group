# Website_Group
Angelica imut dan Asty cantik Pinky Bracelet Website
<!DOCTYPE html>
<html lang="id" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pinky Bracellet</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=Playfair+Display:ital,wght@1,400;1,700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
        }
        .playfair-font {
            font-family: 'Playfair Display', serif;
        }
        .coquette-bg {
            background-image: url("data:image/svg+xml,%3Csvg width='6' height='6' viewBox='0 0 6 6' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='%23fbcfe8' fill-opacity='0.5' fill-rule='evenodd'%3E%3Cpath d='M5 0h1L0 6V5zm1 6v-1L1 6z'/%3E%3C/g%3E%3C/svg%3E");
        }
    </style>
</head>
<body class="bg-pink-50 text-gray-800">

    <!-- Navbar -->
    <header class="sticky top-0 z-50 bg-pink-100/80 backdrop-blur-sm shadow-md">
        <nav class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center gap-4">
                <a href="#home" class="text-xl font-bold playfair-font text-pink-700">Pinky Bracellet</a>
            </div>
            <div class="hidden md:flex gap-6">
                <a href="#beranda" class="hover:text-pink-600 transition-colors">Beranda</a>
                <a href="#tentang" class="hover:text-pink-600 transition-colors">Tentang Kami</a>
                <a href="#produk" class="hover:text-pink-600 transition-colors">Produk</a>
                <a href="#testimoni" class="hover:text-pink-600 transition-colors">Testimoni</a>
                <a href="#pesanan" class="hover:text-pink-600 transition-colors">Formulir Pemesanan</a>
            </div>
            <button id="cart-button" class="relative p-2 bg-pink-300 text-pink-900 rounded-full hover:bg-pink-400 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.153 1.708.7 1.708H17m0-13v10m0-10l4-8H5.4M7 13l-2.293 2.293c-.63.63-.153 1.708.7 1.708H17l-1.6 4H7" />
                </svg>
                <span id="cart-count" class="absolute top-0 right-0 inline-flex items-center justify-center px-2 py-1 text-xs font-bold leading-none text-red-100 transform translate-x-1/2 -translate-y-1/2 bg-red-600 rounded-full">0</span>
            </button>
            <button id="mobile-menu-button" class="md:hidden">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-pink-700" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16m-7 6h7" />
                </svg>
            </button>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-pink-100/90 py-4 text-center space-y-2">
            <a href="#beranda" class="block py-2 hover:bg-pink-200">Beranda</a>
            <a href="#tentang" class="block py-2 hover:bg-pink-200">Tentang Kami</a>
            <a href="#produk" class="block py-2 hover:bg-pink-200">Produk</a>
            <a href="#testimoni" class="block py-2 hover:bg-pink-200">Testimoni</a>
            <a href="#pesanan" class="block py-2 hover:bg-pink-200">Formulir Pemesanan</a>
        </div>
    </header>

    <!-- Main Content -->
    <main class="coquette-bg">
        <!-- Beranda -->
        <section id="beranda" class="container mx-auto px-4 py-16 text-center">
            <h1 class="text-4xl md:text-6xl font-extrabold playfair-font text-pink-800">Pinky Bracellet</h1>
            <h2 class="text-xl md:text-2xl font-semibold text-blue-600 mt-2">12 H - Kelompok 11</h2>
            <p class="text-lg text-gray-600 mb-6">Asty dan Angelica</p>
            <div id="hero-image-container" class="relative mt-8 max-w-2xl mx-auto rounded-xl shadow-xl overflow-hidden animate-pulse bg-gray-200 flex justify-center items-center h-80 md:h-96">
                <span class="text-gray-500">Memuat gambar...</span>
            </div>
            <p class="mt-8 text-lg md:text-xl text-gray-700 max-w-3xl mx-auto">
                Temukan koleksi gelang dan kalung manik-manik yang cantik, lucu, dan menarik. Aksesoris kami dibuat dengan cinta, cocok untuk melengkapi penampilanmu dengan gaya yang unik dan ceria!
            </p>
            <p class="mt-4 text-2xl font-bold text-pink-600">Harga Mulai dari <span class="text-4xl text-blue-600">Rp 5.000</span></p>
            <a href="#produk" class="mt-8 inline-block px-8 py-3 text-lg font-semibold text-white bg-pink-500 rounded-full shadow-lg hover:bg-pink-600 transform transition-transform hover:scale-105">Lihat Koleksi Kami</a>
        </section>

        <!-- Tentang Kami -->
        <section id="tentang" class="container mx-auto px-4 py-16 bg-blue-100 rounded-xl shadow-lg my-12">
            <h2 class="text-3xl md:text-4xl font-bold playfair-font text-blue-800 text-center mb-6">Tentang Kami</h2>
            <div class="grid md:grid-cols-2 gap-8 items-center">
                <img src="https://placehold.co/600x400/b6d4fe/ffffff?text=Pinky+Bracellet" alt="Tim Pinky Bracellet" class="rounded-xl shadow-md mx-auto">
                <div class="space-y-4 text-gray-700">
                    <p>Pinky Bracellet dimulai dari hobi membuat aksesoris manik-manik yang unik dan penuh warna. Kami, Asty dan Angelica, percaya bahwa setiap gadis berhak merasa istimewa tanpa harus merogoh kocek dalam.</p>
                    <p>Semua produk kami dibuat dengan teliti dan penuh kasih sayang, menggunakan bahan-bahan berkualitas untuk memastikan keindahan dan ketahanan. Misi kami adalah menghadirkan aksesoris yang tidak hanya cantik, tetapi juga terjangkau bagi semua remaja.</p>
                    <p>Setiap gelang dan kalung yang kami buat adalah representasi dari gaya yang ceria dan feminin. Kami berharap aksesoris Pinky Bracellet bisa menjadi bagian dari setiap momen indahmu!</p>
                </div>
            </div>
        </section>

        <!-- Produk -->
        <section id="produk" class="container mx-auto px-4 py-16">
            <h2 class="text-3xl md:text-4xl font-bold playfair-font text-pink-800 text-center mb-8">Produk Kami</h2>
            <div id="product-container" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Product cards will be loaded here dynamically -->
                <div class="bg-white rounded-xl shadow-lg p-6 text-center animate-pulse">
                    <div class="w-full h-48 bg-gray-200 rounded-lg"></div>
                    <div class="mt-4 h-6 w-2/3 bg-gray-200 mx-auto rounded"></div>
                    <div class="mt-2 h-4 w-1/2 bg-gray-200 mx-auto rounded"></div>
                    <div class="mt-4 h-10 w-full bg-pink-200 rounded-full"></div>
                </div>
                <div class="bg-white rounded-xl shadow-lg p-6 text-center animate-pulse">
                    <div class="w-full h-48 bg-gray-200 rounded-lg"></div>
                    <div class="mt-4 h-6 w-2/3 bg-gray-200 mx-auto rounded"></div>
                    <div class="mt-2 h-4 w-1/2 bg-gray-200 mx-auto rounded"></div>
                    <div class="mt-4 h-10 w-full bg-pink-200 rounded-full"></div>
                </div>
                <div class="bg-white rounded-xl shadow-lg p-6 text-center animate-pulse">
                    <div class="w-full h-48 bg-gray-200 rounded-lg"></div>
                    <div class="mt-4 h-6 w-2/3 bg-gray-200 mx-auto rounded"></div>
                    <div class="mt-2 h-4 w-1/2 bg-gray-200 mx-auto rounded"></div>
                    <div class="mt-4 h-10 w-full bg-pink-200 rounded-full"></div>
                </div>
            </div>
        </section>

        <!-- Testimoni -->
        <section id="testimoni" class="container mx-auto px-4 py-16">
            <h2 class="text-3xl md:text-4xl font-bold playfair-font text-blue-800 text-center mb-8">Apa Kata Pelanggan Kami?</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-pink-100 rounded-xl shadow-lg p-6 text-center">
                    <p class="italic text-gray-700">"Gelangnya lucu banget! Harganya juga terjangkau, cocok buat jajan anak sekolah. Desainnya juga unik, aku suka banget!"</p>
                    <p class="mt-4 font-semibold text-pink-800">- Siti, 15 tahun</p>
                </div>
                <div class="bg-blue-100 rounded-xl shadow-lg p-6 text-center">
                    <p class="italic text-gray-700">"Kalungnya cantik sekali, pengirimannya juga cepat. Pilihan warnanya gemas-gemas! Bakal beli lagi di sini."</p>
                    <p class="mt-4 font-semibold text-blue-800">- Maya, 18 tahun</p>
                </div>
                <div class="bg-pink-100 rounded-xl shadow-lg p-6 text-center">
                    <p class="italic text-gray-700">"Harga murce, barangnya nggak murahan. Kualitasnya bagus dan desainnya beda dari yang lain. Recommended!"</p>
                    <p class="mt-4 font-semibold text-pink-800">- Dinda, 16 tahun</p>
                </div>
            </div>
        </section>

        <!-- Formulir Pemesanan -->
        <section id="pesanan" class="container mx-auto px-4 py-16">
            <h2 class="text-3xl md:text-4xl font-bold playfair-font text-pink-800 text-center mb-8">Formulir Pemesanan</h2>
            <div id="order-container" class="bg-white rounded-xl shadow-lg p-8 max-w-2xl mx-auto">
                <p id="total-price" class="text-center text-xl font-bold mb-4 text-gray-800 hidden">Total Pesanan: Rp 0</p>
                <form id="order-form" class="space-y-4">
                    <div>
                        <label for="nama" class="block text-gray-700">Nama Lengkap</label>
                        <input type="text" id="nama" name="nama" class="w-full mt-1 p-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-pink-400" required>
                    </div>
                    <div>
                        <label for="alamat" class="block text-gray-700">Alamat Lengkap</label>
                        <textarea id="alamat" name="alamat" rows="3" class="w-full mt-1 p-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-pink-400" required></textarea>
                    </div>
                    <div>
                        <label for="telepon" class="block text-gray-700">Nomor Telepon (WhatsApp)</label>
                        <input type="tel" id="telepon" name="telepon" class="w-full mt-1 p-2 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-pink-400" required>
                    </div>
                    <div>
                        <label class="block text-gray-700">Pilihan Pembayaran</label>
                        <div class="mt-2 space-y-2">
                            <label class="inline-flex items-center">
                                <input type="radio" name="payment-method" value="qris" class="form-radio text-pink-600" checked>
                                <span class="ml-2 text-gray-700">QRIS</span>
                            </label>
                            <label class="inline-flex items-center ml-4">
                                <input type="radio" name="payment-method" value="dana" class="form-radio text-pink-600">
                                <span class="ml-2 text-gray-700">DANA</span>
                            </label>
                        </div>
                    </div>
                    <div id="payment-details" class="bg-gray-50 rounded-lg p-4 text-center border border-dashed border-gray-300">
                        <!-- Payment details will be inserted here -->
                    </div>
                    <button type="submit" class="w-full px-6 py-3 bg-pink-500 text-white font-semibold rounded-full shadow-lg hover:bg-pink-600 transition-colors transform hover:scale-105">Konfirmasi Pesanan</button>
                </form>
                <div class="mt-6 text-center">
                    <p class="text-gray-600 mb-2">Atau, hubungi kami langsung via WhatsApp:</p>
                    <a id="whatsapp-link" href="https://wa.me/6281211234744" target="_blank" class="inline-block px-6 py-3 bg-green-500 text-white font-semibold rounded-full shadow-lg hover:bg-green-600 transition-colors transform hover:scale-105">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 inline-block mr-2" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0C5.373 0 0 5.373 0 12c0 3.313 1.343 6.315 3.515 8.485L1.515 24l2.47-1.485c.954.516 2.02.775 3.102.775C12.627 23.29 18 17.917 18 11.29c0-6.627-5.373-12-12-12zm-2 15.688c-.282.282-.69.423-1.15.423-.46 0-.87-.14-1.15-.423-.28-.28-.42-.69-.42-1.15s.14-.87.42-1.15l1.41-1.41c.28-.28.69-.42 1.15-.42.46 0 .87.14 1.15.42.28.28.42.69.42 1.15s-.14.87-.42 1.15l-1.41 1.41zM15 11.29c0 .63-.12 1.25-.36 1.83-.24.58-.59 1.1-1.05 1.54s-1.04.81-1.63 1.05c-.58.24-1.2.36-1.83.36-1.27 0-2.43-.49-3.32-1.38-.89-.89-1.38-2.05-1.38-3.32 0-1.27.49-2.43 1.38-3.32.89-.89 2.05-1.38 3.32-1.38 1.27 0 2.43.49 3.32 1.38.89.89 1.38 2.05 1.38 3.32z"/></svg>
                        Chat via WhatsApp
                    </a>
                </div>
            </div>
        </section>

    </main>

    <!-- Modal for Cart -->
    <div id="cart-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black bg-opacity-50">
        <div class="bg-white rounded-lg shadow-xl p-6 w-11/12 md:w-1/3">
            <div class="flex justify-between items-center mb-4">
                <h3 class="text-xl font-bold text-gray-800">Keranjang Belanja</h3>
                <button id="close-cart-modal" class="text-gray-500 hover:text-gray-700">&times;</button>
            </div>
            <div id="cart-items" class="space-y-4">
                <p id="empty-cart-message" class="text-center text-gray-500">Keranjang masih kosong.</p>
            </div>
            <div class="mt-6 text-center">
                <p id="cart-total-price" class="text-lg font-bold text-gray-800"></p>
                <a href="#pesanan" id="checkout-button" class="mt-4 inline-block px-6 py-3 bg-pink-500 text-white font-semibold rounded-full hover:bg-pink-600 transition-colors hidden">
                    Lanjut ke Pemesanan
                </a>
            </div>
        </div>
    </div>

    <!-- Modal for Order Success -->
    <div id="success-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-black bg-opacity-50">
        <div class="bg-white rounded-lg shadow-xl p-6 w-11/12 md:w-1/3 text-center">
            <h3 class="text-xl font-bold text-green-600 mb-4">Pesanan Berhasil!</h3>
            <p id="success-message" class="text-gray-700 mb-6"></p>
            <button id="close-success-modal" class="px-6 py-2 bg-pink-500 text-white font-semibold rounded-full hover:bg-pink-600 transition-colors">
                Tutup
            </button>
        </div>
    </div>
    
    <script>
        const API_KEY = ""; // Kunci API akan disediakan secara otomatis
        const API_URL = "https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-image-preview:generateContent?key=" + API_KEY;
        const products = [
            { name: "Gelang Manik Pelangi", price: 15000, description: "Gelang manik warna-warni cerah." },
            { name: "Kalung Hati Pink", price: 20000, description: "Kalung dengan liontin hati pink pastel." },
            { name: "Gelang Bunga daisy", price: 12000, description: "Gelang manik-manik dengan hiasan bunga daisy kecil." },
            { name: "Kalung Manik Bintang", price: 18000, description: "Kalung manik dengan aksen bintang dan bulan." },
            { name: "Set Gelang Couple", price: 20000, description: "Dua gelang manik untuk couple atau sahabat." },
            { name: "Gelang Pita Coquette", price: 10000, description: "Gelang dengan hiasan pita khas gaya coquette." }
        ];

        let cart = [];

        // Loading and showing sections
        document.addEventListener('DOMContentLoaded', () => {
            fetchHeroImage();
            fetchProductImages();
            setupEventListeners();
            updateCartUI();
        });

        // Fetch image for hero section
        async function fetchHeroImage() {
            try {
                const payload = {
                    contents: [{
                        parts: [{
                            text: "Gambar close-up (bokeh, soft focus) seorang gadis remaja dengan rambut panjang yang mengenakan gelang manik-manik pastel dan kalung manik-manik. Tampilkan produk secara jelas. Gaya coquette dengan pita dan bunga, warna dominan pink dan biru pastel. Kualitas fotografi yang tinggi."
                        }]
                    }, {
                        parts: [{
                            text: "Gambar close-up (bokeh, soft focus) seorang gadis remaja dengan rambut panjang yang mengenakan gelang manik-manik pastel dan kalung manik-manik. Tampilkan produk secara jelas. Gaya coquette dengan pita dan bunga, warna dominan pink dan biru pastel. Kualitas fotografi yang tinggi."
                        }]
                    }],
                    generationConfig: {
                        responseModalities: ['TEXT', 'IMAGE']
                    },
                };

                const response = await fetch(API_URL, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                const result = await response.json();
                const base64Data = result?.candidates?.[0]?.content?.parts?.find(p => p.inlineData)?.inlineData?.data;

                if (base64Data) {
                    const imageUrl = data:image/png;base64,${base64Data};
                    const imgElement = document.createElement('img');
                    imgElement.src = imageUrl;
                    imgElement.alt = "Gambar gelang dan kalung Pinky Bracellet";
                    imgElement.className = "w-full h-full object-cover rounded-xl shadow-lg";
                    document.getElementById('hero-image-container').innerHTML = '';
                    document.getElementById('hero-image-container').classList.remove('animate-pulse', 'bg-gray-200');
                    document.getElementById('hero-image-container').appendChild(imgElement);
                } else {
                    console.error('Failed to get image data from API.');
                    document.getElementById('hero-image-container').innerHTML = '<span class="text-red-500">Gagal memuat gambar.</span>';
                }
            } catch (error) {
                console.error('Error fetching hero image:', error);
                document.getElementById('hero-image-container').innerHTML = '<span class="text-red-500">Gagal memuat gambar.</span>';
            }
        }

        // Fetch images for product cards
        async function fetchProductImages() {
            const productContainer = document.getElementById('product-container');
            productContainer.innerHTML = ''; // Clear placeholder
            for (let i = 0; i < products.length; i++) {
                const product = products[i];
                const card = document.createElement('div');
                card.className = "bg-white rounded-xl shadow-lg p-6 text-center flex flex-col items-center animate-pulse bg-gray-100";
                card.innerHTML = <div class="w-full h-48 bg-gray-200 rounded-lg"></div>;
                productContainer.appendChild(card);
            }

            for (let i = 0; i < products.length; i++) {
                const product = products[i];
                const prompt = Foto produk close-up yang menarik untuk ${product.name}. Tampilkan produk dengan gaya fotografi ceria dan feminin. Terdapat manik-manik, pita, dan bunga kecil sebagai hiasan. Kualitas tinggi, warna pastel pink dan biru.
                
                try {
                    const payload = {
                        contents: [{ parts: [{ text: prompt }] }],
                        generationConfig: { responseModalities: ['TEXT', 'IMAGE'] },
                    };
                    const response = await fetch(API_URL, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(payload)
                    });
                    const result = await response.json();
                    const base64Data = result?.candidates?.[0]?.content?.parts?.find(p => p.inlineData)?.inlineData?.data;

                    if (base64Data) {
                        const imageUrl = data:image/png;base64,${base64Data};
                        const card = document.getElementById('product-container').children[i];
                        card.classList.remove('animate-pulse', 'bg-gray-100');
                        card.innerHTML = `
                            <img src="${imageUrl}" alt="${product.name}" class="w-full h-48 object-cover rounded-lg shadow-md mb-4">
                            <h3 class="text-lg font-semibold text-pink-800">${product.name}</h3>
                            <p class="text-sm text-gray-600 mb-2">${product.description}</p>
                            <p class="text-xl font-bold text-blue-600 mb-4">Rp ${product.price.toLocaleString('id-ID')}</p>
                            <button onclick="addToCart(${i})" class="w-full px-4 py-2 bg-pink-400 text-white font-semibold rounded-full hover:bg-pink-500 transition-colors transform hover:scale-105">
                                Tambah ke Keranjang
                            </button>
                        `;
                    } else {
                        throw new Error("No image data");
                    }
                } catch (error) {
                    console.error(Error fetching image for ${product.name}:, error);
                    // Use a placeholder image as a fallback
                    const fallbackImageUrl = https://placehold.co/400x300/fecaca/9d174d?text=${encodeURIComponent(product.name.replace(' ', '+'))};
                    const card = document.getElementById('product-container').children[i];
                    card.classList.remove('animate-pulse', 'bg-gray-100');
                    card.innerHTML = `
                        <img src="${fallbackImageUrl}" alt="${product.name}" class="w-full h-48 object-cover rounded-lg shadow-md mb-4">
                        <h3 class="text-lg font-semibold text-pink-800">${product.name}</h3>
                        <p class="text-sm text-gray-600 mb-2">${product.description}</p>
                        <p class="text-xl font-bold text-blue-600 mb-4">Rp ${product.price.toLocaleString('id-ID')}</p>
                        <button onclick="addToCart(${i})" class="w-full px-4 py-2 bg-pink-400 text-white font-semibold rounded-full hover:bg-pink-500 transition-colors transform hover:scale-105">
                            Tambah ke Keranjang
                        </button>
                    `;
                }
            }
        }

        // Add item to cart
        function addToCart(index) {
            const product = products[index];
            const existingItem = cart.find(item => item.name === product.name);
            if (existingItem) {
                existingItem.quantity++;
            } else {
                cart.push({ ...product, quantity: 1 });
            }
            updateCartUI();
            alertMessage("Produk ditambahkan ke keranjang!");
        }

        // Update cart UI
        function updateCartUI() {
            const cartCount = document.getElementById('cart-count');
            const cartItemsContainer = document.getElementById('cart-items');
            const cartTotalPriceElement = document.getElementById('cart-total-price');
            const emptyCartMessage = document.getElementById('empty-cart-message');
            const checkoutButton = document.getElementById('checkout-button');

            const totalItems = cart.reduce((sum, item) => sum + item.quantity, 0);
            const totalPrice = cart.reduce((sum, item) => sum + (item.price * item.quantity), 0);
            
            cartCount.textContent = totalItems;
            
            cartItemsContainer.innerHTML = '';
            if (cart.length > 0) {
                emptyCartMessage.style.display = 'none';
                checkoutButton.style.display = 'inline-block';
                cart.forEach((item, index) => {
                    const itemDiv = document.createElement('div');
                    itemDiv.className = "flex justify-between items-center bg-pink-50 p-3 rounded-lg";
                    itemDiv.innerHTML = `
                        <p class="text-gray-700">${item.name} x ${item.quantity}</p>
                        <p class="font-semibold text-pink-700">Rp ${(item.price * item.quantity).toLocaleString('id-ID')}</p>
                    `;
                    cartItemsContainer.appendChild(itemDiv);
                });
                cartTotalPriceElement.textContent = Total: Rp ${totalPrice.toLocaleString('id-ID')};
                document.getElementById('total-price').textContent = Total Pesanan: Rp ${totalPrice.toLocaleString('id-ID')};
                document.getElementById('total-price').style.display = 'block';
            } else {
                emptyCartMessage.style.display = 'block';
                checkoutButton.style.display = 'none';
                cartTotalPriceElement.textContent = '';
                document.getElementById('total-price').style.display = 'none';
            }
        }

        // Event listeners setup
        function setupEventListeners() {
            // Mobile menu
            document.getElementById('mobile-menu-button').addEventListener('click', () => {
                document.getElementById('mobile-menu').classList.toggle('hidden');
            });
            document.getElementById('mobile-menu').querySelectorAll('a').forEach(link => {
                link.addEventListener('click', () => {
                    document.getElementById('mobile-menu').classList.add('hidden');
                });
            });

            // Cart Modal
            const cartModal = document.getElementById('cart-modal');
            document.getElementById('cart-button').addEventListener('click', () => {
                cartModal.classList.remove('hidden');
                cartModal.classList.add('flex');
            });
            document.getElementById('close-cart-modal').addEventListener('click', () => {
                cartModal.classList.remove('flex');
                cartModal.classList.add('hidden');
            });
            
            // Order Form
            const orderForm = document.getElementById('order-form');
            const paymentDetailsDiv = document.getElementById('payment-details');
            const paymentMethods = orderForm.elements['payment-method'];
            const successModal = document.getElementById('success-modal');

            // Initial payment details display
            updatePaymentDetails(paymentMethods.value);

            paymentMethods.forEach(radio => {
                radio.addEventListener('change', (event) => {
                    updatePaymentDetails(event.target.value);
                });
            });

            orderForm.addEventListener('submit', (e) => {
                e.preventDefault();
                const nama = document.getElementById('nama').value;
                const alamat = document.getElementById('alamat').value;
                const telepon = document.getElementById('telepon').value;
                const paymentMethod = paymentMethods.value;
                const totalPrice = cart.reduce((sum, item) => sum + (item.price * item.quantity), 0);

                let orderMessage = Halo Pinky Bracellet, saya ingin memesan produk-produk berikut:\n\n;
                cart.forEach(item => {
                    orderMessage += - ${item.name} (${item.quantity} pcs) - Rp ${(item.price * item.quantity).toLocaleString('id-ID')}\n;
                });
                orderMessage += \nTotal Harga: Rp ${totalPrice.toLocaleString('id-ID')}\n;
                orderMessage += \nNama: ${nama}\n;
                orderMessage += Alamat: ${alamat}\n;
                orderMessage += Telepon: ${telepon}\n;
                orderMessage += Metode Pembayaran: ${paymentMethod === 'qris' ? 'QRIS' : 'DANA'}\n;
                
                const whatsappLink = https://wa.me/6281211234744?text=${encodeURIComponent(orderMessage)};
                window.open(whatsappLink, '_blank');

                document.getElementById('success-message').textContent = "Terima kasih atas pesanannya! Silakan lanjutkan pembayaran dan konfirmasi melalui WhatsApp yang akan otomatis terbuka.";
                successModal.classList.remove('hidden');
                successModal.classList.add('flex');

                cart = []; // Reset cart
                updateCartUI();
                orderForm.reset();
            });

            document.getElementById('close-success-modal').addEventListener('click', () => {
                successModal.classList.remove('flex');
                successModal.classList.add('hidden');
            });
        }
        
        function updatePaymentDetails(method) {
            const paymentDetailsDiv = document.getElementById('payment-details');
            if (method === 'qris') {
                paymentDetailsDiv.innerHTML = `
                    <p class="font-semibold text-gray-800">Scan QRIS di bawah ini:</p>
                    <img src="https://placehold.co/200x200/ffb6c1/ffffff?text=QRIS+DANA" alt="QRIS DANA" class="mx-auto mt-2 rounded-lg">
                `;
            } else if (method === 'dana') {
                paymentDetailsDiv.innerHTML = `
                    <p class="font-semibold text-gray-800">Bayar melalui DANA:</p>
                    <p class="text-sm mt-2">Pilih salah satu cara pembayaran di bawah ini:</p>
                    <div class="mt-4 space-y-2">
                        <a href="https://link.dana.id/minta?full_url=https://qr.dana.id/v1/281012012023052082211598" target="_blank" class="w-full inline-block px-4 py-2 bg-blue-500 text-white rounded-full hover:bg-blue-600 transition-colors">
                            Bayar Via Link DANA
                        </a>
                        <div class="flex items-center justify-center">
                            <span id="dana-number" class="text-lg font-semibold text-blue-800 select-all mr-2">081211234744</span>
                            <button type="button" onclick="copyToClipboard('081211234744')" class="p-1 text-gray-500 hover:text-gray-700 focus:outline-none">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor"><path d="M8 3a1 1 0 011-1h2a1 1 0 110 2H9a1 1 0 01-1-1z" /><path d="M6 3a2 2 0 00-2 2v11a2 2 0 002 2h8a2 2 0 002-2V5a2 2 0 00-2-2 1 1 0 01-1-1H9a1 1 0 01-1 1zm-3 8a1 1 0 100 2h1a1 1 0 100-2H3z" /></svg>
                            </button>
                        </div>
                    </div>
                `;
            }
        }
        
        function copyToClipboard(text) {
            const tempInput = document.createElement('input');
            tempInput.value = text;
            document.body.appendChild(tempInput);
            tempInput.select();
            try {
                document.execCommand('copy');
                alertMessage('Nomor berhasil disalin!');
            } catch (err) {
                console.error('Gagal menyalin: ', err);
            }
            document.body.removeChild(tempInput);
        }

        function alertMessage(message) {
            const modal = document.createElement('div');
            modal.className = 'fixed inset-0 z-[100] flex items-center justify-center bg-black bg-opacity-50';
            modal.innerHTML = `
                <div class="bg-white rounded-lg shadow-xl p-6 text-center w-11/12 md:w-1/4">
                    <p class="text-gray-800">${message}</p>
                </div>
            `;
            document.body.appendChild(modal);
            setTimeout(() => {
                modal.remove();
            }, 2000);
        }
    </script>
</body>
</html>
