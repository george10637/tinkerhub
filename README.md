<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tinker Hub NSSCE</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>TINKER HUB NSSCE</h1>
    <header>
        <nav class="navbar">
            <ul>
              
               <li><a href="contact.html">Contact</a></li>
               <li><a href="announcement.html">Announcement</a></li>
            </ul>
        </nav>
    </header>
    <BR>

    <div id="nssce">
        <h2><u><b>NSS COLLEGE OF ENGINEERING</b></u></h2>
        <h3>N S S College of Engineering, Palakkad is one of the most reputed, premier engineering educational institution in Kerala affiliated to APJ Abdul Kalam Technological University. It was established in 1960 by Nair Service Society under the leadership of late Bharatha Kesari Mannathu Padmanabhan, during the second five year plan with the assistance of the Central and State Government under the grant-in-aid scheme. The college has an enviable heritage and legacy of grooming brilliant engineering professionals who later made their mark in industrial and other sectors of the country and abroad. At present, the institution offers B.Tech degree courses in six branches and M.Tech degree courses in Communication Engineering, Power Electronics, Computer Science & Engineering, Structural Engineering, Computer Integrated Manufacturing, and Biomedical Engineering. The College is an approved research Place of APJ Abdul Kalam Technological University.
            Situated in NSS Nagar at Akathethara, 9 km from Palakkad town, the Campus is easily accessible, being only 4 km from the Palakkad Railway Junction, and is only 5 km from the renowned Malampuzha Gardens. Spread over 125 acres, the college includes an administrative block, separate blocks for each department, a library block and four hostels including one for ladies. Nestling among verdant foothills, the institution is a tranquil and serene setting for higher education.</h3>
           <center>
            <img src="college.jpg"
            alt="NSS COLLEGE"
            >
           </center>
        </div>
        <hr>
        <div id="thnss">

            <Center>
                <img src="tinkerhubnssce_logo.jpeg">
            </Center>
        <pre>TinkerHub NSSCE, the non-profit founded in 2014, is an organization working in alignment with the sustainable development goals of quality education, decent work, and economic growth.

            Skill poverty has long-lasting repercussions in the Indian job environment where skill mismatch and underqualified graduates are the reasons for a massive unemployment rate. In a few years, unemployment is feared to become the cause of a greater economic disruption, with aftershocks that will have social, political, and economic dimensions.
            
            TinkerHub Foundation was born out of our understanding of the above. Today, the community hosts, co-hosts, and partners with learning initiatives all over the country. For the next two years, our goal is to enable industry-relevant technology education to over 10,000 students across 300 colleges.
            
            Learning Path is a virtual library with different paths or roadmaps listed, which a student can follow at any point in their journey of learning tech.</pre>    
        
            
        </div>
    
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Announcement</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .slider {
            position: relative;
            max-width: 600px;
            margin: auto;
            overflow: hidden;
        }
        .slides {
            display: flex;
            transition: transform 0.5s ease-in-out;
        }
        .slide {
            min-width: 100%;
            transition: opacity 0.5s;
        }
        .navigation {
            position: absolute;
            top: 50%;
            width: 100%;
            display: flex;
            justify-content: space-between;
            transform: translateY(-50%);
        }
        .nav-btn {
            background-color: rgba(0, 0, 0, 0.5);
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="slider">
        <div class="slides">
            <img src="community.jpg" alt="Image 1" class="slide">
            <img src="Screenshot_23-4-2025_22186_www.instagram.com.jpeg" alt="Image 2" class="slide">
            <img src="panel.jpg" alt="Image 3" class="slide">
        </div>
        <div class="navigation">
            <button class="nav-btn" id="prev">❮</button>
            <button class="nav-btn" id="next">❯</button>
        </div>
    </div>

    <script>
        const slides = document.querySelector('.slides');
        const images = document.querySelectorAll('.slide');
        const totalSlides = images.length;
        let currentIndex = 0;

        document.getElementById('next').addEventListener('click', () => {
            currentIndex = (currentIndex + 1) % totalSlides;
            slides.style.transform = `translateX(-${currentIndex * 100}%)`;
        });

        document.getElementById('prev').addEventListener('click', () => {
            currentIndex = (currentIndex - 1 + totalSlides) % totalSlides;
            slides.style.transform = `translateX(-${currentIndex * 100}%)`;
        });
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTACT</title>
    <link rel="stylesheet" href="style.css">
   <div id="contact">
   <center>
    <h1><u><b>Contact Us</b></u></h1>
   </center>
   <pre id="contactwrite">"Connect with Us
    At Tinker Hub, innovation starts with collaboration.<br>
     Whether you’re brimming with ideas, need guidance, or are curious about what we do, we’d love to hear from you! Reach out to us through the contact form below, drop us an email, or connect with us on social med.<br>
      Together, let’s keep igniting creativity and building a vibrant tech community. Your thoughts and feedback are always welcome!"</pre>
   </div>
   <a href="https://www.instagram.com/tinkerhub.nssce/?utm_source=ig_web_button_share_sheet">
    <img src="insta.jpeg"
    height="100px"
    width="100px"/>
   </a>
   <a href="https://www.linkedin.com/company/tinkerhubnssce/">
    <img src="lindin.jpeg"
    height="100px";
    width="100px"/>
   </a>
   </head>
<body>
    
</body>
</html>
