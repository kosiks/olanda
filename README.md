<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descoperă Olanda</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #003399;
            color: white;
            text-align: center;
            padding: 20px;
        }

        nav {
            background-color: #0055cc;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 20px;
            margin: 20px;
        }

        h1, h2 {
            color: #003399;
        }

        p {
            font-size: 1.1rem;
            line-height: 1.6;
        }

        ul {
            list-style-type: disc;
            margin-left: 40px;
        }

        blockquote {
            font-style: italic;
            margin: 20px 0;
            padding-left: 20px;
            border-left: 5px solid #003399;
        }

        footer {
            background-color: #003399;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        .flag-image {
            display: block;
            margin: 20px auto;
            width: 30%;
            border: 2px solid #003399;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .gallery img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .gallery img:hover {
            transform: scale(1.05);
            opacity: 0.8;
        }

        .gallery figcaption {
            text-align: center;
            margin-top: 10px;
            font-weight: bold;
            color: #003399;
        }

        /* CSS pentru imagini responsive */
        img {
            max-width: 100%;
            height: auto;
        }

    </style>
</head>
<body>

    <header>
        <h1>Descoperă Olanda</h1>
    </header>

    <nav>
        <a href="#despre" title="Mergi la Despre Olanda">Despre Olanda</a>
        <a href="#locuri" title="Mergi la Locuri de Vizitat">Locuri de Vizitat</a>
        <a href="#traditii" title="Mergi la Tradiții Olandeze">Tradiții</a>
        <a href="mailto:contact@exemplu.com" title="Trimite email">Contact</a>
    </nav>

    <section id="despre">
        <h2>Despre Olanda</h2>
        <p><strong>Olanda</strong>, cunoscută și sub denumirea oficială de Regatul Țărilor de Jos, este un stat din nord-vestul Europei, faimos pentru peisajele sale plată, canale, mori de vânt și câmpuri de lalele.</p>
        <p><em>Olanda este un loc unde tradițiile se îmbină armonios cu inovația modernă</em>. Capitala Olandei, <strong>Amsterdam</strong>, este un oraș vibrant, cu muzee celebre și canale pitorești.</p>
        <img src="https://cdn11.bigcommerce.com/s-2lbnjvmw4d/images/stencil/original/products/2962/5202/hollandflag__26010.1738246320.jpg" alt="Steagul Olandei" class="flag-image" title="Steagul Olandei">
    </section>

    <section id="locuri">
        <h2>Locuri de Vizitat</h2>
        <p>Olanda este plină de locuri deosebite, care atrag turiști din întreaga lume. Unele dintre cele mai vizitate locuri sunt:</p>
        <ul>
            <li><b>Amsterdam</b> - <a href="https://www.iamsterdam.com" target="_blank" title="Mai multe despre Amsterdam">Află mai multe</a></li>
            <li><b>Grădina de Lalele Keukenhof</b> - Un loc magic unde vizitatorii pot admira mii de lalele înflorite.</li>
            <li><b>Morile de vânt Zaanse Schans</b> - Un loc pitoresc unde vizitatorii pot vedea mori de vânt tradiționale.</li>
        </ul>
        
        <div class="gallery">
            <figure>
                <img src="https://career-advice.jobs.ac.uk/wp-content/uploads/Netherlands3-e1634207438966.jpg.optimal.jpg" alt="Peisaj Olanda" title="Peisaj Olanda">
                <figcaption>Peisaj în Olanda</figcaption>
            </figure>
            <figure>
                <img src="https://www.visitingthedutchcountryside.com/wp-content/uploads/2019/09/best-fun-indoor-markets-game-halls-to-visit-amsterdam-netherlands.jpg" alt="Piață în Amsterdam" title="Piață în Amsterdam">
                <figcaption>Piață în Amsterdam</figcaption>
            </figure>
            <figure>
                <img src="https://www.worldatlas.com/r/w1200/upload/e7/fa/05/amsterdam-culture-netherlands.jpg" alt="Cultura în Amsterdam" title="Cultura în Amsterdam">
                <figcaption>Cultura în Amsterdam</figcaption>
            </figure>
            <figure>
                <img src="https://lp-cms-production.imgix.net/2023-03/GettyImages-937057490.jpeg?sharp=10&vib=20&w=1200&w=600&h=400" alt="Canale Amsterdam" title="Canale Amsterdam">
                <figcaption>Canale din Amsterdam</figcaption>
            </figure>
            <figure>
                <img src="https://student-cms.prd.timeshighereducation.com/sites/default/files/styles/default/public/2021-08/iStock-885965442.jpg?itok=o2HDKavx" alt="Universitate în Olanda" title="Universitate în Olanda">
                <figcaption>Universitate în Olanda</figcaption>
            </figure>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Descoperă Olanda. Toate drepturile rezervate.</p>
    </footer>

</body>
</html>
