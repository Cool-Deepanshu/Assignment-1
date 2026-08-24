# Assignment-1
A comprehensive HTML webpage for a fictional learning platform like TuteDude is a fantastic way to practice and demonstrate proficiency in using HTML tags and structures. This project will guide you through constructing a well-organised and semantic webpage that showcases a wide array of HTML capabilities.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Menu - Taco Table</title>
     <style>
     body {
         font-family: Arial, sans-serif;
         margin: 20px;
     }
     h2 {
         margin-bottom: 10px;
     }
     table {
         width: 100%;
         max-width: 800px;
         border-collapse: collapse;
         text-align: left;
     }
     th, td {
         border: 1px solid #000;
         padding: px 8px;
         font-size: 14px;
     }
     th {
         background-color: #f9f9f9;
     }
     .table-title {
         font-weight: bold;
         font-size: 15px;
     }
 </style>
</head>
<body>
    <!-- Welcome Section -->
    <header>
        <h1>Welcome to <mark>TuteDude</mark></h1>
        <em>A project designed by <strong>TuteDude</strong> to learn HTML
            <br> <br>
          Best TuteDude in town since 2021  
        </em>
        <!-- Navigation -->
        <nav>
            <ul>
                <li><a href="https://www.tutedude.com/about" target="_blank">About TD</a></li>
                <li><a href="https://www.tutedude.com" target="_blank">Our Menu</a></li>
                <li><a href="https://www.tutedude.com/trivia" target="_blank">Taco Trivia</a></li>
                <li><a href="https://www.tutedude.com/extras" target="_blank">Extras</a></li>
                <li><a href="https://www.tutedude.com/about" target="_blank">Feedback Form</a></li>
                <li><a href="https://www.tutedude.com/about" target="_blank">Contact</a></li>
            </ul>
           <figure><img src="/Assets/image/tute.png" alt="TuteDude Logo" width="400px" height="300px">
            <figcaption>TuteDude and a Drink</figcaption>
        </figure>

    </header>
    <hr>
    <!-- Main Content -->
    <main>
        <!-- About TD Section -->
        <section>
            <h2>About <abbr title="TuteDude">TD</abbr></h2>

            <article>
                <pre style="font-family: Arial, sans-serif;">
    <abbr title="TuteDude">TD</abbr> was founded in <time datetime="2021">2021</time>. This demo project was created by <strong>TuteDude</strong> for learning all major HTML tags. <br><br>
            Level up your career with expert mentorship & internships for FREE  </pre>
            </article>
        </section>
        <hr>
        <!-- Our Menu Section -->
        <section>
            <h2>Our Menu</h2>
            <h3 style="text-align: center;">TuteDude Complete Taco Menu</h3>

            <!-- Menu Table -->
    <table>
        <thead>


            <!-- Primary Headers -->
            <tr>
                <th rowspan="2">Category</th>
                <th rowspan="2" colspan="">Type</th>
                <th colspan="2">Small Portion</th>
                <th colspan="2">Large Portion</th>
            </tr>
            <!-- Sub Headers -->
            <tr>
                <th>Qty</th>
                <th>Price</th>
                <th>Qty</th>
                <th>Price</th>
            </tr>
        </thead>
        <tbody>
            <!-- SECTION 1: TuteDude -->
            <tr>
                <td rowspan="3"><strong>TuteDude</strong></td>
                <td colspan="">Crunchy (Fast Food)</td>
                <td>1</td>
                <td>$1.50</td>
                <td>3</td>
                <td>$3.25</td>
            </tr>
            <tr>
                <td colspan="">Crunchy (Maggie)</td>
                <td>1</td>
                <td>$1.75</td>
                <td>3</td>
                <td>$3.50</td>
            </tr>
            <tr>
                <td colspan="">Crunchy (Veggie)
                    <br> Nutrient Info
                    <br>
                      <table style="width: 60%">
  <tr>
      <td colspan="3"><strong>Nutrient</strong></td>
      <td colspan="3"><strong>Value</strong></td>
  </tr>
  <tr>
      <td colspan="3">Calories</td>
      <td colspan="3">150 kcal</td>
  </tr>
  <tr>
      <td colspan="3">Protein</td>
      <td colspan="3">5 g</td>
  </tr>
  <tr>
      <td colspan="3">Fiber</td>
      <td colspan="3">4 g</td>
  </tr>
  </table>
                </td>
                <td rowspan="">1</td>
                <td rowspan="">$1.25</td>
                <td rowspan="">3</td>
                <td rowspan="">$3.00</td>
            </tr>
            <!-- SECTION 2: Soft TuteDude -->
            <tr>
                <td rowspan="2"><strong>Soft TuteDude</strong></td>
                <td colspan="">Soft (Beans)</td>
                <td>2</td>
                <td>$3.50</td>
                <td>4</td>
                <td>$.50</td>
            </tr>
            <tr>
                <td colspan="">Soft (Veggie)</td>
                <td>2</td>
                <td>$3.00</td>
                <td>4</td>
                <td>$5.50</td>
            </tr>

            <!-- SECTION 3: Combos -->
            <tr>
                <td rowspan="2"><strong>Combos</strong></td>
                <td colspan="">2 Crunchy + Drink
        </td>
                <td colspan="2">$4.50</td>
                <td colspan="2" rowspan="2">N/A</td>
            </tr>
            <tr>
                <td colspan="">2 Soft + Drink <br>
                    <label style="text-align: center;">Combo Meals Nutrition <br> Facts
                        <table>
        <tr>
            <td  colspan="2"><strong>Item</strong></td>
            <td colspan="2"><strong>Calories</strong></td>
            <td colspan="2"><strong>Sugar</strong></td>
        </tr>
    <tr>
        <td colspan="2">Soft Taco</td>
        <td colspan="2">200 kcal</td>
        <td colspan="2">2 g</td>
    </tr>
    <tr>
        <td colspan="2">Drink</td>
        <td colspan="2">120 kcal</td>
        <td colspan="2">25 g</td>
    </tr>
    <tr><strong>
        <td colspan="2"><b>Total</b></td>
        <td colspan="2"><b>320 kcal</b></td>
        <td colspan="2"><b>27 g</b></td>
    </tr>
</table>
                </td>
                <td colspan="2" rowspan="">$5.00</td>
            </tr>
    
    
   <!-- Section 4: Extras -->
            <tr>
                <td rowspan="4" colspan=""><strong>Extras</strong></td>
                <td colspan="">Chips & Salsa</td>
                
                <td colspan="4">$2.00</td>
                </tr>
            <tr>
                <td colspan="">Guacamole</td>
                <td colspan="4">$1.50</td>
             </tr> 
<tfoot>
             <tr>
                <td colspan="12"><strong>Average Meal Price Range: $2.00 - $6.50</strong></td>
            </tr>
            </tfoot>
        </tbody>
    </table>
    <br>
<a href="" rel="noopener noreferrer"> ! Back to Top</a>
<hr>
<!-- Taco Tirvia Section -->
<section>
    
<aside>
<h2>Taco Tirvia</h2>
<details>
    
    <summary>When did TuteDude first appear in the United States?</summary>
    <p>TuteDude first appeared in the United States in 2021.</p>

</details>

</aside>

</section>
<hr>
<!-- Media Fun -->
 <section>
    <h2>Media Fun</h2>

    <h4>Listen to Taco Music</h4>
    <br>
    <audio controls>
        <source src="/Assets/Audio/audio.mp3" type="audio/mpeg" >
    </audio>
    <br>
<h4>Watch Taco Video</h4>
    <br>
    <video controls width="250px">
        <source src="/Assets/Video/video.mp4" type="video/mp4">
    </video>
    <br>
</section>

<hr>
<section>
    <h2>Give Us Your Feedback</h2>

    <form action="/submit-feedback" method="post">
        <fieldset>
            <legend>Your Info</legend>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <br><br>
            <label for="favorite-taco">Favorite Taco:</label>
            <select name="favorite-taco" id="favorite-taco">
                <option value="" hidden>Select your favorite taco</option>
                <option value="soft-taco">Soft Taco</option>
                <option value="hard-taco">Hard Taco</option>
                <option value="fish-taco">Crunchy Taco</option>
            </select>
        </fieldset>
<fieldset>
            <legend>Your Message</legend>
            <label for="feedback">Message:</label><br>
            <textarea id="feedback" name="feedback" rows="4" cols="50" required></textarea><br><br>
        </fieldset>
        <input type="submit" value="Submit">
</section>
</main>

<hr>
<!-- Footer -->
<footer>


<!-- Contact Us -->
<section>
    <h2>Contact Us</h2>
    <p style="font-style: italic;">TuteDude
        <br>123 Taco Street
        <br>Taco Town, TX 75000
        <br><a href="mailto:info@tutedude.com">info@tutedude.com</a>
        <br><br>
    &copy; 2025 TuteDude. All rights reserved.
    </p>

    <hr>
       
       </section>
</footer> 
</body>
</html>
