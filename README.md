<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata dan Materi Jaringan Komputer</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gradient-to-r from-pink-300 via-purple-300 to-blue-300 text-gray-800 h-screen overflow-y-auto">
    <div class="container mx-auto p-6">
        <!-- Header -->
        <header class="text-center mb-10">
            <h1 class="text-4xl font-bold text-blue-700 mb-4">Jaringan Komputer</h1>
            <p class="text-lg text-gray-700">Welcome to feb's web!!</p>
        </header>

        <div class="flex flex-col lg:flex-row gap-8">
            <!-- Biodata Section -->
            <div class="bg-white shadow-lg rounded-lg p-6 border border-blue-400 w-full lg:w-1/3">
                <h2 class="text-2xl font-bold text-blue-600 mb-4">Biodata</h2>
                <div class="flex flex-col items-center">
                    <img src="./feby.jpg" alt="Foto" class="w-30 h-40 rounded-full shadow-lg border-4 border-pink-500 mb-4">
                    <div class="text-center">
                        <p class="text-lg"><strong>Nama:</strong> Khansa Feby Olivia</p>
                        <p class="text-lg"><strong>NIM:</strong> 607012400126</p>
                        <p class="text-lg"><strong>Kelas:</strong> 48-02</p>
                        <p class="text-lg"><strong>Jurusan:</strong> D3 Sistem Informasi</p>
                        <p class="text-lg"><strong>Mata Kuliah:</strong> Jaringan Komputer</p>
                    </div>
                </div>
            </div>

            <!-- Materi Jaringan Komputer Section -->
            <div class="bg-white shadow-lg rounded-lg p-6 border border-purple-400 w-full lg:w-2/3">
                <h2 class="text-2xl font-bold text-purple-600 mb-4">Perantara Jaringan Komputer: Switch</h2>
                <div class="flex flex-col lg:flex-row items-center lg:items-start">
                    <img src="./switch.jpg" alt="Switch" class="w-48 h-48 rounded-lg shadow-md mb-6 lg:mb-0 lg:mr-6">
                    <div>
                        <p class="mb-4"><strong>Fungsi:</strong> Switch adalah perangkat jaringan yang berfungsi untuk menghubungkan beberapa perangkat dalam satu jaringan lokal (LAN) dan memfasilitasi komunikasi antar perangkat tersebut.</p>
                        <p class="mb-4"><strong>Jenis:</strong></p>
                        <ul class="list-disc pl-5 text-purple-700 mb-4">
                            <li>Unmanaged Switch</li>
                            <li>Managed Switch</li>
                            <li>Smart Switch</li>
                        </ul>
                        <p class="text-sm text-gray-500">Sumber: <a href="https://id.wikipedia.org/wiki/Jaringan_komputer" target="_blank" class="text-blue-500 hover:underline">Wikipedia</a></p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Links Section -->
        <div class="bg-white shadow-lg rounded-lg p-6 border border-pink-400 mt-10">
            <h2 class="text-2xl font-bold text-pink-600 mb-4">Tutorial dan Referensi</h2>
            <div class="flex flex-col lg:flex-row justify-around">
                <a href="https://www.hostingadvice.com/how-to/" target="_blank" class="text-blue-500 hover:underline">Tutorial Hosting</a>
                <a href="https://drive.google.com/file/d/1w7ePo8jeZp9h49mZI79SeqJ2_bGbc7pv/view?usp=sharing" target="_blank" class="text-blue-500 hover:underline">Tutorial Pembuatan Website</a>
            </div>
        </div>
    </div>

    <footer class="bg-blue-400 text-white text-center py-3">
        <p>&copy; 2024 Biodata Web</p>
    </footer>

</body>
</html>
