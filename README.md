<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tourist Spots in Region 9</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f1f1f1;
            color: #333;
        }

        header {
            background: linear-gradient(to right, #2c3e50, #34495e);
            color: white;
            text-align: center;
            padding: 40px 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        h1 {
            margin: 0;
            font-size: 3rem;
            letter-spacing: 2px;
        }

        .container {
            width: 80%;
            margin: 30px auto;
            background-color: white;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            font-size: 2rem;
            color: #2c3e50;
            text-align: center;
            margin-bottom: 30px;
        }

        .tourist-list {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .tourist-spot {
            background-color: #ecf0f1;
            padding: 20px;
            border-radius: 10px;
            transition: background-color 0.3s, transform 0.3s;
        }

        .tourist-spot:hover {
            background-color: #bdc3c7;
            transform: translateY(-5px);
        }

        .tourist-spot img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .tourist-spot h3 {
            font-size: 1.5rem;
            color: #34495e;
            margin-top: 15px;
            text-transform: capitalize;
            transition: color 0.3s;
        }

        .tourist-spot h3:hover {
            color: #e74c3c;
        }

        .tourist-spot p {
            font-size: 1rem;
            color: #7f8c8d;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
            font-size: 0.9rem;
        }

        #myBtn {
            display: none;
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 99;
            background-color: #2c3e50;
            color: white;
            border: none;
            border-radius: 50%;
            padding: 15px;
            cursor: pointer;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            font-size: 1.5rem;
        }

        #myBtn:hover {
            background-color: #34495e;
            transform: scale(1.1);
        }

        @media (max-width: 768px) {
            .tourist-list {
                grid-template-columns: 1fr 1fr;
            }
        }

        @media (max-width: 480px) {
            .tourist-list {
                grid-template-columns: 1fr;
            }
        }

        .intro-text {
            color: #2c3e50;
            font-size: 1.2rem;
            line-height: 1.6;
            margin-bottom: 20px;
        }

    </style>
</head>
<body>
    
    <header>
        <h1>Tourist Spots in Region 9</h1>
    </header>

    <div class="container">

        <p class="intro-text">
            The Zamboanga Peninsula, also known as Region 9 in the Philippines, is an enchanting blend of cultural diversity, historic charm, and natural splendor. Located in the Mindanao Island group, it comprises three provinces - Zamboanga del Norte, Zamboanga del Sur, and Zamboanga Sibugay - along with the highly urbanized city of Zamboanga. This region invites you to bask in its pristine beaches, trek through its lush mountains, and immerse in its rich cultural heritage.
        </p>

        <h2>Discover the Beauty of Region 9</h2>
        <div class="tourist-list">
            <div class="tourist-spot">
                <img src="pink.jpg" alt="Sta. Cruz Island">
                <h3>Sta. Cruz Island (Zamboanga City)</h3>
                <p>Known for its unique pink sand beaches, Sta. Cruz Island offers a rare and beautiful natural phenomenon.</p>
            </div>
            <div class="tourist-spot">
                <img src="falls.jpg" alt="Merloquet Falls">
                <h3>Merloquet Falls (Zamboanga City)</h3>
                <p>A stunning two-tiered waterfall surrounded by lush forests, perfect for those who love nature and adventure.</p>
            </div>
            <div class="tourist-spot">
                <img src="Pasonanca.jpg" alt="Pasonanca Natural Park">
                <h3>Pasonanca Natural Park (Zamboanga City)</h3>
                <p>Home to over 600 species of trees, this natural park is a peaceful retreat and a sanctuary for wildlife lovers.</p>
            </div>
            <div class="tourist-spot">
                <img src="once islas.webp" alt="Once Islas">
                <h3>Once Islas (Zamboanga City)</h3>
                <p>A newly opened eco-cultural spot with pristine beaches and mangrove areas, offering a fresh take on sustainable tourism.</p>
            </div>
            <div class="tourist-spot">
                <img src="dapitan.jpg" alt="Rizal Shrine">
                <h3>Rizal Shrine (Dapitan City)</h3>
                <p>A historical landmark commemorating Dr. Jose Rizal, located at the site where he was exiled in the late 19th century.</p>
            </div>
            <div class="tourist-spot">
                <img src="dakak.avif" alt="Dakak Beach">
                <h3>Dakak Beach (Dapitan City)</h3>
                <p>Famous for its white sand and crystal-clear waters, Dakak Beach is perfect for relaxation and water sports.</p>
            </div>
            <div class="tourist-spot">
                <img src="Fantasyland.webp" alt="Fantasy Land">
                <h3>Fantasy Land, Dapitan City, Zamboanga del Norte</h3>
                <p>This theme park offers various rides and attractions, including a horror house, roller coaster, and grand carousel, making it a perfect family destination.</p>
            </div>
            <div class="tourist-spot">
                <img src="fort pilar.jpg" alt="Fort Pilar">
                <h3>Fort Pilar, Zamboanga City</h3>
                <p>A 17th-century military defense fortress, now a regional museum showcasing various archeological artifacts and a popular religious shrine, making it a historical and cultural landmark.</p>
            </div>
            <div class="tourist-spot">
                <img src="blue lagoon.jpg" alt="Mampang Blue Lagoon">
                <h3>Mampang Blue Lagoon, Zamboanga City</h3>
                <p>Known for its mesmerizing blue-green waters, the lagoon is a great spot for swimming and picnics. Its natural beauty offers a perfect backdrop for nature photography.</p>
            </div>
            <div class="tourist-spot">
                <img src="labuan.jpg" alt="Labuan Public Market">
                <h3>Labuan Public Market, Zamboanga City</h3>
                <p>Immerse yourself in the local culture by exploring this bustling market. It's a great place to buy local produce, fresh seafood, traditional sweets, and handicrafts.</p>
            </div>
            <div class="tourist-spot">
                <img src="port.JPG" alt="Pulauan Wharf">
                <h3> NortPulauan Wharf, Dapitan City, Zamboanga del Norte</h3>
                <p>Serving as the main gateway to Dipolog and Dapitan, this wharf is also a perfect spot to enjoy the picturesque view of the sunrise and the serene waters of the Mindanao Sea.</p>
            </div>
            <div class="tourist-spot">
                <img src="cawa.jpg" alt="Cawa-Cawa Boulevard">
                <h3>Cawa-Cawa Boulevard, Zamboanga City</h3>
                <p>Popularly known as the 'Iloilo River Esplanade of Zamboanga', this place offers a great spot for strolling, jogging, or just enjoying the scenic view of the Basilan Strait, especially during sunset.</p>
            </div>
            <div class="tourist-spot">
                <img src="limpapa.jpg" alt="Limpapa Bridge">
                <h3>Limpapa Bridge, Zamboanga City</h3>
                <p>This picturesque bridge offers stunning views of the valley below and the surrounding hills, making it a great spot for photography.</p>
            </div>
            <div class="tourist-spot">
                <img src="Aliguay.webp" alt="Aliguay Island">
                <h3>Aliguay Island, Dapitan City, Zamboanga del Norte</h3>
                <p>An ideal location for divers and snorkelers, this island offers a vibrant marine sanctuary with beautiful coral reefs and diverse marine life.</p>
            </div>
            <div class="tourist-spot">
                <img src="Sindangan.jpg" alt="Sindangan Bay">
                <h3>Sindangan Bay, Sindangan, Zamboanga del Norte</h3>
                <p>Home to numerous fish species, this bay is a haven for fishing enthusiasts. Its serene environment and beautiful sunset also make it an ideal place for relaxation.</p>
            </div>
            <div class="tourist-spot">
                <img src="Serenity.jpg" alt="Serenity Farm and Resort">
                <h3>Serenity Farm and Resort, Tampilisan, Zamboanga del Norte</h3>
                <p>This resort is famous for its botanical garden filled with different kinds of trees, plants, and flowers. It's a perfect place for relaxation and nature walks.</p>
            </div>
            <div class="tourist-spot">
                <img src="Baluno.jpg" alt="Baluno Lake">
                <h3>Baluno Lake, Zamboanga City</h3>
                <p>This serene and beautiful lake offers a tranquil environment perfect for picnics and fishing.</p>
            </div>
            <div class="tourist-spot">
                <img src="Zamboanga.jpg" alt="Zamboanga Golf Course and Beach Park">
                <h3>Zamboanga Golf Course and Beach Park, Zamboanga City</h3>
                <p>A well-maintained golf course and beach in one, this place offers sports, relaxation, and recreation, all in one place.</p>
            </div>
            <div class="tourist-spot">
                <img src="RT.jpg" alt="Cocolandia">
                <h3>Cocolandia, R.T. Lim, Zamboanga Sibugay</h3>
                <p>Known for its vast coconut plantation, visitors can learn about coconut farming and enjoy coconut-based products and dishes.</p>
            </div>
            <div class="tourist-spot">
                <img src="island.jpg" alt="Delusom Island">
                <h3>Delusom Island, Zamboanga del Sur</h3>
                <p>This untouched island offers white sandy beaches, crystal clear waters, and vibrant marine life, perfect for beach camping, swimming, and snorkeling.</p>
            </div>
            <div class="tourist-spot">
                <img src="Moro.jpg" alt="Moro Watch Tower">
                <h3>Moro Watch Tower, Dapitan City, Zamboanga del Norte</h3>
                <p>A historical landmark, the tower was used as a lookout for marauding pirates during Spanish times. Visitors can enjoy a panoramic view of Dapitan Bay from the top.</p>
            </div>
            <div class="tourist-spot">
                <img src="Sibutad.webp" alt="Buton Marine Sanctuary">
                <h3>Buton Marine Sanctuary, Sibutad, Zamboanga del Norte</h3>
                <p>This marine sanctuary is a haven for various fish species and sea turtles. It's an ideal spot for snorkeling and diving.</p>
            </div>
            <div class="tourist-spot">
                <img src="Canelar.jpg" alt="Canelar Barter Trade Center">
                <h3>Canelar Barter Trade Center, Zamboanga City</h3>
                <p>Here, you can experience a unique shopping experience where goods are both sold and bartered. The market is known for Malaysian and Indonesian products, local sweets, and handicrafts.</p>
            </div>
            <div class="tourist-spot">
                <img src="Pulongbato.jpg" alt="Mount Pulumbato">
                <h3>Mount Pulumbato, Rizal, Zamboanga del Norte</h3>
                <p>This mountain offers challenging trails for hikers leading to a rewarding panoramic view of the surrounding landscapes from the top.</p>
            </div>
            <div class="tourist-spot">
                <img src="hermosa.jpg" alt="Hermosa Festival">
                <h3>Hermosa Festival, Zamboanga City</h3>
                <p>This festival, held every October, is a month-long celebration showcasing the city's Chavacano heritage and devotion to Our Lady of the Pillar. Highlights include a regatta, street dance competition, and various cultural shows.</p>
            </div>
            <div class="tourist-spot">
                <img src="RizalDapitan.jpg" alt="Rizal Landing Site">
                <h3>Rizal Landing Site, Dapitan City, Zamboanga del Norte</h3>
                <p>This landmark commemorates the spot where Dr. Jose Rizal first set foot in Dapitan.</p>
            </div>
            <div class="tourist-spot">
                <img src="pantalan.jpg" alt="Pantalan Lagoon">
                <h3>Pantalan Lagoon, Zamboanga City</h3>
                <p>A hidden gem, this tranquil lagoon is a great place for boating and fishing. It's also a perfect place for birdwatching, with various bird species inhabiting the area.</p>
            </div>
        </div>

        <p class="intro-text">
            Region 9, or the Zamboanga Peninsula, is a realm that invites visitors to explore and immerse in its cultural heritage, historical landmarks, and natural attractions. Its offering ranges from pink sand beaches and scenic waterfalls to centuries-old landmarks and lively local festivals, ensuring that every type of traveler has something to enjoy.
        </p>

        <p class="intro-text">
            Visiting these places not only allows you to experience the Peninsula's charm but also supports local tourism and community development. So, when planning your next adventure, why not make it Region 9 and witness firsthand the vibrant tapestry of culture, history, and natural wonders that it has to offer.
        </p>

    </div>

    <footer>
        <p>&copy; bairasasao3@gmail.com 2025 Region 9 Tourist Spots. All rights reserved.</p>
    </footer>

    <button onclick="topFunction()" id="myBtn" title="Go to top">↑</button>

    <script>
        var mybutton = document.getElementById("myBtn");

        window.onscroll = function() {scrollFunction()};

        function scrollFunction() {
            if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
                mybutton.style.display = "block";
            } else {
                mybutton.style.display = "none";
            }
        }

        function topFunction() {
            document.body.scrollTop = 0;
            document.documentElement.scrollTop = 0;
        }
    </script>

</body>
</html>
