<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>5th Annual Music at the Ranch</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Inter Font -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f8f8; /* Light background */
        }
        /* Custom styles for potential interactivity or specific elements */
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        .bg-gradient-ranch {
            background-image: linear-gradient(to right top, #a78bfa, #8b5cf6, #7c3aed, #6d28d9, #5b21b6);
        }
    </style>
</head>
<body class="antialiased text-gray-800">
    <div class="min-h-screen flex flex-col items-center py-10 px-4 sm:px-6 lg:px-8">
        <div class="max-w-4xl w-full bg-white rounded-3xl shadow-xl overflow-hidden">
            <!-- Header Section -->
            <div class="relative bg-gradient-ranch p-8 sm:p-12 text-white text-center rounded-t-3xl">
                <!-- Logo Image - Top Left -->
                <!-- IMPORTANT: Replace the 'src' attribute below with the actual URL of your JP logo image -->
                <img src="https://scontent-lax3-2.xx.fbcdn.net/v/t39.30808-6/277106388_286032467031362_8959783665361382380_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=UxKiDjfbhcoQ7kNvwGr2iMz&_nc_oc=Adl1rWh10ZPPaiANWwWqsRiJEk-M6K1yRpCLoO83fggaDU4AdKNKJjcUYjSYdO-gINbMJDarN7eXGcrYNXSU1BCo&_nc_zt=23&_nc_ht=scontent-lax3-2.xx&_nc_gid=ZPp7e7gYYBgQQS02mv7Ajg&oh=00_AfMNIUp00-fJNEfTQZ56mNJpJWetqbkSPmmxZcapXDz_VQ&oe=684BB0FF" alt="JP Pritchard Foundation Logo" class="absolute top-4 left-4 w-20 h-20 sm:w-24 sm:h-24 rounded-full shadow-lg object-cover">

                <!-- Background image for header -->
                <!-- IMPORTANT: Replace the 'src' attribute below with the actual URL of your desired background image -->
                <div class="absolute inset-0 bg-cover bg-center opacity-20" style="background-image: url('https://scontent-lax3-1.xx.fbcdn.net/v/t1.6435-9/71348714_10220216521420181_519132125836869632_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=86c6b0&_nc_ohc=Iu09vUx1l-AQ7kNvwEa7oPC&_nc_oc=Adm9F1Wn15KD3jZAaEilA9ztwL9Pv2j2sCIYSGTZWU36V3CviK_Sl1at-tp8hWVxYZ0vlKpJwqGDs7JQOnG82-Rs&_nc_zt=23&_nc_ht=scontent-lax3-1.xx&_nc_gid=wq2pdiiqv0p4ChnK5eF96w&oh=00_AfOeko1kJVpoS7zUU6sSzBTA9kkmkp1uLVmpkNjguU3Naw&oe=686D4FB6');"></div>

                <!-- Moved Logo Image - Top Right -->
                <!-- IMPORTANT: Replace the 'src' attribute below with the actual URL of your desired logo for the top right -->
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSH7g3fMjRI3S-HFDKaelyAyj2tCR9vwe478Q&s" alt="Top Right Logo" class="absolute top-4 right-4 w-20 h-20 sm:w-24 sm:h-24 rounded-full shadow-lg object-cover">


                <div class="relative z-10">
                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight mb-4">
                        5th Annual Music at the Ranch
                    </h1>
                    <p class="text-xl sm:text-2xl font-semibold mb-2">
                        Presented: JP Pritchard Charitable Foundation & TBK Bank
                    </p>
                    <p class="text-lg sm:text-xl font-medium">
                        A day of music, community, and giving back! ❤️
                    </p>
                </div>
            </div>

            <!-- Event Details Section -->
            <div class="p-6 sm:p-8 lg:p-10 grid grid-cols-1 md:grid-cols-2 gap-8">
                <div>
                    <h2 class="text-2xl sm:text-3xl font-bold text-indigo-700 mb-4 flex items-center">
                        <svg class="w-7 h-7 mr-3 text-indigo-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z" clip-rule="evenodd"></path></svg>
                        Event Details 🗓️
                    </h2>
                    <ul class="space-y-3 text-lg">
                        <li><strong class="font-semibold text-gray-700">Date & Time:</strong> August 9th, 12-5 PM ⏰</li>
                        <li><strong class="font-semibold text-gray-700">Location:</strong> K&J Ranch, 10434 CR 250, Durango 📍</li>
                        <li><strong class="font-semibold text-gray-700">Donation:</strong> $50 per person 💲</li>
                    </ul>
                    <!-- Link for Get Your Tickets Now button -->
                    <a href="https://partiful.com/e/9D6Eg6LtLbC1VlVN4tUt" target="_blank" class="mt-6 inline-block bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 ease-in-out transform hover:scale-105">
                        Get Your Tickets Now! ✨
                    </a>
                </div>

                <div>
                    <h2 class="text-2xl sm:text-3xl font-bold text-indigo-700 mb-4 flex items-center">
                        <svg class="w-7 h-7 mr-3 text-indigo-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M18 3a1 1 0 00-1.447-.894L10 6.006 3.447 2.106A1 1 0 002 3v14a1 1 0 001.447.894L10 13.994l6.553 3.894A1 1 0 0018 17V3z"></path></svg>
                        What to Expect 🎉
                    </h2>
                    <ul class="list-disc list-inside text-lg space-y-2">
                        <li>Live Music by <strong class="font-semibold text-gray-700">BLACK VELVET BAND</strong> 🎸</li>
                        <li>Dynamic Sounds from <strong class="font-semibold text-gray-700">THE JACKSON MARTIN PROJECT</strong> 🎤</li>
                        <li>Delicious <strong class="font-semibold text-gray-700">LUNCH</strong> 🍔</li>
                        <li>Exciting <strong class="font-semibold text-gray-700">SILENT AUCTION</strong> 🎁</li>
                        <li><strong class="font-semibold text-gray-700">2nd Annual Pickleball & Golf Invitational Winners Announced</strong> 🏆</li>
                    </ul>
                </div>
            </div>

            <!-- Beneficiaries Section -->
            <div class="bg-indigo-50 p-6 sm:p-8 lg:p-10 border-t border-b border-indigo-100">
                <h2 class="text-2xl sm:text-3xl font-bold text-indigo-700 mb-6 text-center flex items-center justify-center">
                    <svg class="w-7 h-7 mr-3 text-indigo-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M11.077 14.846A10.038 10.038 0 0110 15c-4.478 0-8.268-2.943-9.543-7a9.97 9.97 0 011.047-1.802A10.038 10.038 0 0110 5c4.478 0 8.268 2.943 9.543 7a9.97 9.97 0 01-1.047 1.802zm-5.077-.154v.154H9v-3.077h2v3.077h3.923v-.154l-.447-1.048c-.02-.047-.042-.09-.064-.132A10.038 10.038 0 0110 15c-4.478 0-8.268-2.943-9.543-7A9.97 9.97 0 011.047 5.198 10.038 10.038 0 0110 5c4.478 0 8.268 2.943 9.543 7a9.97 9.97 0 01-1.047 1.802z" clip-rule="evenodd"></path></svg>
                    ⭐ Benefiting Incredible Causes ⭐
                </h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 text-center">
                    <div class="p-4 bg-white rounded-xl shadow-md card-hover transition duration-200 flex flex-col items-center">
                        <!-- IMPORTANT: Replace 'https://example.com' with the actual URL for Manna Soup Kitchen -->
                        <a href="https://www.mannasoupkitchen.org/?gad_source=1&gad_campaignid=16492513368&gbraid=0AAAAAoaz7Zrrf-eLCK7LRu4EQHjuoua30&gclid=CjwKCAjw6ZTCBhBOEiwAqfwJdwugCHaaFsz0MW4lDe8nsG4nImoAuy2wOeF_jfET3B45Xb2OcVOF_RoCdA8QAvD_BwE" target="_blank">
                            <img src="https://images.squarespace-cdn.com/content/v1/6592da05553b6a2789a4e1d3/b6c28143-dd8e-4afa-92ea-ffabd6e84d5b/manna-horiz-logo.jpg?format=1500w" alt="Manna Soup Kitchen Logo" class="mb-2 w-20 h-20 object-contain">
                        </a>
                        <p class="font-semibold text-lg text-gray-700">MANNA SOUP KITCHEN 🍲</p>
                    </div>
                    <div class="p-4 bg-white rounded-xl shadow-md card-hover transition duration-200 flex flex-col items-center">
                        <!-- IMPORTANT: Replace 'https://example.com' with the actual URL for Young People in Recovery -->
                        <a href="https://youngpeopleinrecovery.org/" target="_blank">
                            <img src="https://youngpeopleinrecovery.org/wp-content/uploads/2022/06/National_Logo-Long-Yellow.png" class="mb-2 w-20 h-20 object-contain">
                        </a>
                        <p class="font-semibold text-lg text-gray-700">YOUNG PEOPLE IN RECOVERY 🌱</p>
                    </div>
                    <div class="p-4 bg-white rounded-xl shadow-md card-hover transition duration-200 flex flex-col items-center">
                        <!-- IMPORTANT: Replace 'https://example.com' with the actual URL for Tanta Vida Rescue -->
                        <a href="https://www.facebook.com/groups/1685079355309205/" target="_blank">
                            <img src="https://images.squarespace-cdn.com/content/v1/66d4a91386c2bc76d2105fe0/df0d7118-27c1-4ae6-8f93-b0b52c66b834/tantavidaperros_logo.png?format=1000w" alt="Tanta Vida Rescue Logo" class="mb-2 w-20 h-20 object-contain">
                        </a>
                        <p class="font-semibold text-lg text-gray-700">TANTA VIDA RESCUE 🐾</p>
                    </div>
                    <div class="p-4 bg-white rounded-xl shadow-md card-hover transition duration-200 flex flex-col items-center">
                        <!-- IMPORTANT: Replace 'https://example.com' with the actual URL for Annie's Orphans -->
                        <a href="https://www.anniesk9orphans.org/" target="_blank">
                            <img src="https://images.squarespace-cdn.com/content/v1/651b1d29fa3ff4418caed3cf/641ffd48-b53a-4ca0-8d4d-5965b093827b/annies-k9-orphans-durango-co-dog-shelter-logo2.jpg?format=1500w" alt="Annie's Orphans Logo" class="mb-2 w-20 h-20 object-contain">
                        </a>
                        <p class="font-semibold text-lg text-gray-700">ANNIE'S ORPHANS 🧒</p>
                    </div>
                </div>
            </div>

            <!-- About Foundation Section -->
            <div class="p-6 sm:p-8 lg:p-10 bg-gray-50">
                <h2 class="text-2xl sm:text-3xl font-bold text-indigo-700 mb-4 flex items-center">
                    <svg class="w-7 h-7 mr-3 text-indigo-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd"></path></svg>
                    About The JP Pritchard Charitable Foundation 💡
                </h2>
                <!-- Image near foundation description -->
                <!-- IMPORTANT: Replace the 'src' attribute below with the actual URL of the foundation image -->
                <div class="flex justify-center mb-6">
                    <img src="https://scontent-lax3-2.xx.fbcdn.net/v/t39.30808-6/482326418_956656553302280_7864111915873499223_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=cc71e4&_nc_ohc=EoFoQC6oIYQQ7kNvwGrQja1&_nc_oc=AdmaZ0EQpq2zljqx3sdYSkv_-o-WNKMcja9VI-MwxvMmMUmrxFFpJ1ArWnt51nMFr_q1Im4TBCZ-jwuxeHX3jHSH&_nc_zt=23&_nc_ht=scontent-lax3-2.xx&_nc_gid=zhBsK-PV9_7RftPvbV17FA&oh=00_AfO7nVKZuZ6yjznCQ-3XVgrH0kydePxhGZKQ3HMNa6MJiQ&oe=684BAFA6" alt="Image related to JP Pritchard Foundation" class="w-full max-w-sm rounded-lg shadow-md object-cover">
                </div>
                <p class="text-base sm:text-lg leading-relaxed text-gray-700">
                    The JP Pritchard Charitable Foundation is named in honor of our son JP, who was tragically killed five years ago. JP, who was born in the Buffalo NY area, and grew up in Durango, was an outstanding musician, chef/cook and friend to many. He was known to literally give the shirt off his back to people in need. His family started the Foundation to keep JP's memory and extraordinary empathy for others alive through helping those in need. 🤗
                </p>
                <!-- Updated button to link to Facebook -->
                <a href="https://facebook.com/JPPritchardFoundation" target="_blank" class="mt-4 inline-block bg-gray-200 hover:bg-gray-300 text-gray-800 font-semibold py-2 px-6 rounded-full transition duration-300 ease-in-out transform hover:scale-105">
                    Check out our Facebook
                </a>
            </div>

            <!-- Sponsors Section -->
            <div class="p-6 sm:p-8 lg:p-10 border-t border-gray-200">
                <h2 class="text-2xl sm:text-3xl font-bold text-indigo-700 mb-6 text-center flex items-center justify-center">
                    <svg class="w-7 h-7 mr-3 text-indigo-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M9 6a3 3 0 11-6 0 3 3 0 016 0zM17.555 17.309A1 1 0 0117 17H3a1 1 0 01-.447-1.894L.553 13.106A1 1 0 011 12h18a1 1 0 01.447.894l-2 4A1 1 0 0117.555 17.309z"></path></svg>
        🤝 Our Valued Sponsors 🤝
                </h2>
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-6 items-center justify-center">
                    <!-- Sponsor logos - IMPORTANT: Replace the 'href' attribute of each <a> tag below with the actual URL of the sponsor's website -->
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://www.deltaim.com/" target="_blank">
                            <img src="https://images.squarespace-cdn.com/content/v1/66994d3d02615c69656b3a58/e480e44c-afd6-47c6-af8c-9e3aaddc4158/Screenshot+2024-12-16+at+7.09.54%E2%80%AFPM.png?format=1500w" alt="DELTA INVESTMENT MANAGEMENT" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://icapital.com/" target="_blank">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/ICapital.svg/500px-ICapital.svg.png" alt="iCapital" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://www.selkirk.com/?srsltid=AfmBOoqwmOMVz-7vPpRCBgrLVqWa6hyalSQxn3mgMj4NF-x63byfA97P" target="_blank">
                            <img src="https://www.selkirk.com/cdn/shop/files/selkirk-logo-icon_eda15e15-374d-4ef8-a4e3-41de8af659b4.png?v=1723152534&width=100" alt="SELKIRK" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://www.wellsgroupdurango.com/" target="_blank">
                            <img src="https://production-uploads.fastly.propertybase.com/assets/uploads/setting/company_header_logo/29850/c2de033a74b59aebad967879209b27ca.png?width=700&optimize=low&auto=webp" alt="Wells Group REAL ESTATE" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://www.alpinebank.com/" target="_blank">
                            <img src="https://www.alpinebank.com/custom/alpinebank/image/logo-2x.png" alt="Alpine Bank" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://www.innovatoretfs.com/" target="_blank">
                            <img src="https://pbs.twimg.com/profile_banners/827541598732955648/1646506271/1500x500" alt="INNOVATOR" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://www.northstar65.com/" target="_blank">
                            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXHX3kY_CWN98t7GBymsh4HTIB3t_mZx-slQ&s" alt="NORTHSTAR FINANCIAL & RETIREMENT PLANNING" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://www.firsteagle.com/" target="_blank">
                            <img src="https://mma.prnewswire.com/media/1776972/First_Eagle_Investments_Logo.jpg?p=twitter" alt="First Eagle Investments" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://www.ftportfolios.com/" target="_blank">
                            <img src="https://www.ftportfolios.com/common/images/FTPlogo.jpg" alt="First Trust" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                    <div class="p-3 flex justify-center items-center rounded-lg bg-gray-100 h-20">
                        <a href="https://www.downtowndurango.org/sportinggoods" target="_blank">
                            <img src="https://www.downtowndurango.org/assets/graphics/BID-Logo.jpg" alt="down town SPORTS" class="max-h-full max-w-full object-contain">
                        </a>
                    </div>
                </div>
            </div>

            <!-- Footer Section -->
            <div class="bg-gray-800 text-white p-6 sm:p-8 lg:p-10 text-center rounded-b-3xl">
                <p class="text-sm mb-2">
                    <strong class="font-semibold">Contact Wells Group:</strong> 970.259.6680 📞 |
                    <a href="http://www.WellsGroupDurango.com" target="_blank" class="text-indigo-300 hover:underline">www.WellsGroupDurango.com 🌐</a>
                </p>
                <p class="text-xs">
                    A 501(c)(3) Tax Exempt Organization | Tax ID # 84-4768093
                </p>
            </div>
        </div>
    </div>
</body>
</html>
