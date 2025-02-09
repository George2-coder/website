<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Face Your Fears</title>
    <style>
        /* Aesthetic background image */
        body {
            background-image: url('web image.jpg'); /* Replace with your image path */
            background-size: cover;
            background-position: center;
            font-family: Arial, sans-serif;
            color: rgb(255, 255, 255);
            margin: 0;
            padding: 0;
        }

        header {
            text-align: center;
            padding: 100px;
            font-size: 2.5em;
            color: rgb(251, 251, 251);
        }

        section {
            margin: 30px;
        }

        /* Center the 'About' section */
        section h2 {
            text-align: center;
            font-size: 2.5em;
            font: comic ;
        }

        section p {
            text-align: center;
            font-size: 2em;
            max-width: 1000px;
            margin: 0 auto;
            margin-bottom: 100px;
        }

        /* Horizontal layout for select elements */
        .select-container {
            display: grid;
            justify-content: center;
            gap: 40px;
        }

        select {
            padding: 10px;
            font-size: 1em;
            border-radius: 500px;
            border: 1px solid #ffffffa0;
            cursor: block;
        }

        .select-container img {
            width: 30px;
            height: 30px;
            margin-right: 10px;
            border-radius: 15px;
            
             
            
        }
        
        
        /* Icon styling for the selects */
        .icon-wrapper {
            display: flex;
            align-items: center;
          
            
           
        }
    </style>
    <script>
        function openPage(selectId) {
            const selectedValue = document.getElementById(selectId).value;
            if (selectedValue) {
                window.open(selectedValue, "_blank");
            }
        }
    </script>
</head>

<body>
    <header>
        <h1>Real freedom comes when those things which scared you the most don't scare you anymore</h1>
    </header>

    <section>
        <h2>About:</h2>
        <p>
            Face Your Fears is a groundbreaking website designed to help individuals confront and overcome their fears,
            promoting emotional healing and personal growth. Whether you’re dealing with anxiety, phobias, or self-doubt,
            we offer a safe, supportive environment to face your fears at your own pace. We provide you with videos and
            podcasts that help you in your healing process. You just have to believe in yourself! FearLess is not just a
            website; it's your companion in the journey toward emotional freedom, helping you unlock your full potential
            by transforming fear into a source of strength.

        </p>
    </section>

    <!-- Horizontal Layout for Select Options -->
    <section>
        
        <h2>Choose Your Resources</h2>
        <div class="select-container">
            <!-- Video Recommendation -->
            <div class="icon-wrapper">
                <img src="video icon.jpg" alt="Video Icon">
                <select id="phobiaSelect" onchange="openPage('phobiaSelect')">
                    <option value="">--Select Video--</option>
                    <option value="phobia1.html">Acrophobia (Fear of Heights)</option>
                    <option value="phobia2.html">Claustrophobia (Fear of Enclosed Spaces)</option>
                    <option value="phobia3.html">Trypanophobia (Fear of Injection)</option>
                    <option value="phobia4.html">Nosophobia (Fear of Disease)</option>
                    <option value="phobia5.html">Thanatophobia (Fear of Death)</option>
                    <option value="phobia6.html">Traumatophobia (Fear of Injury)</option>
                    <option value="phobia7.html">Ophidiophobia (Fear of Snakes)</option>
                    <option value="phobia8.html">Socialphobia (Fear of Social Situations)</option>
                    <option value="phobia9.html">Claustrophobia (Fear of Confined Spaces)</option>
                    <option value="phobia10.html">Mysophobia (Fear of Microbes)</option>
                    <option value="phobia11.html">Arachnophobia (Fear of Spiders)</option>
                    <option value="phobia12.html">Hemophobia (Fear of Blood)</option>
                    <option value="phobia13.html">Glossophobia (Fear of Public Speaking)</option>
                    <option value="phobia14.html">Amaxophobia (Fear of Driving)</option>
                    <option value="phobia15.html">Phonophobia (Fear of Loud Noises)</option>
                </select>
            </div>

            <!-- Podcast Recommendation -->
            <div class="icon-wrapper">
                <img src="podcast icon.jpg" alt="Podcast Icon">
                <select id="podcastSelect" onchange="openPage('podcastSelect')">
                    <option value="">--Select Podcast--</option>
                    <option value="pod.html">Search for Podcasts</option>
                </select>
            </div>

            <!-- Book Recommendation -->
            <div class="icon-wrapper">
                <img src="books icon.jpg" alt="Book Icon">
                <select id="bookSelect" onchange="openPage('bookSelect')">
                    <option value="">--Select Book--</option>
                    <option value="book.html">Search for Books</option>
                </select>
                
            </div>
        </div>
    </section>

</body>

</html>
