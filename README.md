# Static Website: Typography

Aoife Conleavy is a novelist who has been writing about her travels for nearly two decades. Before the launch of her new novel Tide Blade, which features the stories of real-life characters in Morocco, the author wants to spruce up her professional website. You’ll modify the typography on her site, changing the size, style, and font families, to make the page easier to read.

Using your understanding of typography, help Aoife Conleavy improve the readability of her site for her readers.

## Finished Website

![image](https://github.com/abemsq/typography-website/blob/master/image.png)

## HTML
```
<!DOCTYPE html>
<html>
<head>
  <title>Morocco</title>
  <link rel="stylesheet" type="text/css" href="styles/reset.css">
  <link rel="stylesheet" type="text/css" href="styles/style.css">
  <link href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Merriweather:ital@0;1&family=Work+Sans:wght@400;500;800&display=swap" rel="stylesheet">
</head>
<body>
  <!-- Header -->
  <nav class="header">
    <span class="logo">AOFIE CONLEAVY</span>
    <ul>
      <li><a href="#">TRAVELS</a></li>
      <li><a href="#">FICTION</a></li>
      <li><a href="#">CONTACT</a></li>
    </ul>
  </nav>

  <!-- Banner -->
  <div class="banner">
    <h2>DEC 20XX</h2>
    <h1>Morocco</h1>
  </div>

  <!-- Journal -->
  <div class="journal">
    <div class="first photo">
      <div class="image-container">
        <img src="https://content.codecademy.com/courses/freelance-1/unit-6/project-morocco/photo1.png">
      </div>
      <span class="caption">A convoy of camels criss-crossing the crests of the Sahara</span>
    </div>
    <p>
      <span class="first-letter">I</span> am in the Great Sahara Desert for the third sundown in a row. Fouad and I pass back and forth a sun-bleached map of the stars. It’s more of a tug-of-war to be honest. With what remains of the daylight, we commit to memory the positions of spots on the page. We hope to find some correlation in its negative, which slides overhead as the sun rapidly dies.
    </p>
    <p>
      "Navigating by night is always easier." Fouad flicks these English words as ash from a cigarette. "You’ll see."
    </p>
    <p>
      "We won't see anything. That's my point!"
    </p>
    <p>
      How did we get here?
    </p>
    <p>
      It started eight days ago when I arrived in Malilla on the boat from Malaga. The sun hit me like a judgement as I stepped onto the gangplank. A bit about Morocco:  
    </p>
    <div class="photo">
      <div class="image-container">
        <img src="https://content.codecademy.com/courses/freelance-1/unit-6/project-morocco/photo2.png">
      </div>
      <span class="caption">The long and winding road to Merrakec</span>
    </div>
    <p>
      Morocco has a population of over 33.8 million and an area of 446,550 km2 (172,410 sq mi). Its capital is Rabat, and the largest city is Casablanca. Other major cities include Marrakesh, Tangier, Tetouan, Sale, Fes, Agadir, Meknes, Oujda, Kenitra, and Nador. A historically prominent regional power, Morocco has a history of independence not shared by its neighbours.
    </p>
    <span class="quote">"Navigating by night is always easier."</span>
    <p>
      Since the foundation of the first Moroccan state by Idris I in 789, the country has been ruled by a series of independent dynasties, reaching its zenith under the Almoravid and Almohad dynasty, spanning parts of Iberia and Northwestern Africa. Marinid and Saadi dynasties continued the struggle against foreign domination, and Morocco remained the only North-African country to avoid Ottoman occupation. 
    </p>
    <p>
      The Alaouite dynasty, the current ruling dynasty, seized power in 1666. In 1912 Morocco was be divided into a French and Spanish protectorates, with an international zone in Tangier, and regained its independence in 1956. Moroccan culture is a blend of Arab, indigenous Berber, Sub-Saharan African, and European influences.
    </p>
    <div class="photo">
      <div class="image-container">
        <img src="https://content.codecademy.com/courses/freelance-1/unit-6/project-morocco/photo3.png">
      </div>
      <span class="caption">A stall at the Jemaa El Fnaa street market</span>
    </div>
    <p>
      Morocco claims the non-self-governing territory of Western Sahara as its Southern Provinces. Morocco annexed the territory in 1975, leading to a guerrilla war with indigenous forces until a cease-fire in 1991. Peace processes have thus far failed to break the political deadlock.
    </p>
    <p>
      Morocco is a constitutional monarchy with an elected parliament. The King of Morocco holds vast executive and legislative powers, especially over the military, foreign policy and religious affairs. Executive power is exercised by the government, while legislative power is vested in both the government and the two chambers of parliament, the Assembly of Representatives and the Assembly of Councillors. The king can issue decrees called dahirs which have the force of law. He can also dissolve the parliament after consulting the Prime Minister and the president of the Constitutional court.
    </p>
    <span class="quote">“Navigating by night is always easier.”</span>
    <p>
      Morocco's predominant religion is Islam, and the official languages are Arabic and Tamazight. Moroccan dialect, referred to as Darija, and French are also widely spoken. Morocco is an influential member of the Arab League and a part of the Union for the Mediterranean. It has the fifth largest economy of Africa.
    </p>
    <div class="photo">
      <div class="image-container">
        <img src="https://content.codecademy.com/courses/freelance-1/unit-6/project-morocco/photo4.png">
      </div>
      <span class="caption">The desert at night is strange and beautiful</span>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <div class="image-container">
      <img src="https://content.codecademy.com/courses/freelance-1/unit-6/project-morocco/author.png">
    </div>
    <div class="content">
      <p>
        <span class="author">Aoife Donleavy</span> has been writing on her travels for over two decades.
        After graduating from the <em>Idaho Writers' Workshop</em>, she piloted a biplane on a two-year voyage from <em>Anchorage</em>, <em>Alaska</em> to <em>Isafjorour</em>, <em>Iceland</em> stopping along the way for adventures throughout Europe.
      </p>
      <p>
        Since then, she has camped on all seven continents, and has been recognized worldwide for her spare, ageless prose. Aoife's new novel, <em>Tide Blade</em>, is currently available from <em>Walrus Publishing</em>. 
      </p>
    </div>
  </footer>
</body>
</html>
```

## CSS
```
html {
    font-size: 18px;
  }
  
  @media only screen and (max-width: 1000px) {
    html {
      font-size: 16px;
    }
  }
  
  @media only screen and (max-width: 680px) {
    html {
      font-size: 14px;
    }
  }
  
  /* Header */
  
  .header {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 4.44rem;
    padding: 0 12%;
    background-color: white;
    box-shadow: 0 2px 6px 0 rgba(0, 0, 0, 0.05);
    font-family: Verdana, sans-serif;
    font-size: .77rem;
    font-weight: bold;
  }
  
  .header .logo {
    flex-grow: 1;
    color: #ffb78c;
  }
  
  .header li {
    display: inline;
    padding-right: 2.22rem;
  }
  
  .header li a {
    text-decoration: none;
    color: #4a4a4a;
  }
  
  @media only screen and (max-width: 550px) {
    .header {
      flex-direction: column;
    }
  
    .header .logo {
      flex-grow: 0;
    }
  }
  
  /* Banner */
  
  .banner {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 50rem;
    background: url("https://content.codecademy.com/courses/freelance-1/unit-6/project-morocco/banner.jpg") center center no-repeat;
    background-size: cover;
    color: #ffb78c;
  }
  
  .banner h2 {
    padding: .55rem 0;
    border-top: 4px solid #ffb78c;
    border-bottom: 4px solid #ffb78c;
    font-size: 1.44rem;
    letter-spacing: 2px;
    font-weight: 500;
    font-family: "Work Sans" "Arial" sans-serif;
  }
  
  .banner h1 {
    padding-top: 1.11rem;
    font-size: 11rem;
    font-weight: 900;
    font-family: "Abril Fatface" sans-serif;
  }
  
  @media only screen and (max-width: 750px) {
    .banner {
      height: 40rem;
    }
  
    .banner h1 {
      font-size: 8rem;
    }
  }
  
  @media only screen and (max-width: 530px) {
    .banner {
      height: 30rem;
    }
  
    .banner h1 {
      font-size: 6rem;
    }
  }
  
  /* Journal */
  
  .journal {
    padding: 0 25% 4rem 25%;
    background-color: rgb(254, 231, 218);
    color: #4a4a4a;
    font-family: "Work Sans" serif;
  }
  
  .photo {
    width: 75%;
    padding: 1.11rem;
    border-radius: 5px;
    margin: 0 auto 4.44rem auto;
    background-color: white;
    font-family: "Merriweather" serif;
  }
  
  .photo .image-container {
    overflow: hidden;
    margin-bottom: 1.11rem;
  }
  
  .photo .image-container img {
    width: 100%;
  }
  
  .photo .caption {
    font-style: italic;
  }
  
  .photo.first {
    position: relative;
    top: -2.77rem;
    margin-bottom: 1.67rem;
  }
  
  .journal p {
    padding-bottom: 2.77rem;
    font-size: 1.5rem;
    line-height: 1.4em;
  }
  
  .journal .first-letter {
    float: left;
    padding-right: 1.4rem;
    font-family: "Abril Fatface", serif;
    font-size: 7.44rem;
    color: #10b0d8;
    line-height: 0.87em;
  }
  
  .quote {
    display: block;
    padding: 4.44rem 0;
    margin-bottom: 3.33rem;
    border-top: 4px solid black;
    border-bottom: 4px solid black;
    text-align: center;
    font-size: 3.55rem;
    font-weight: 800;
    line-height: 1.2em;
  }
  
  @media only screen and (max-width: 680px) {
    .journal {
      padding: 0 10% 4rem 10%;
    }
  }
  
  /* Footer */
  
  footer {
    display: flex;
    align-items: center;
    padding: 0 1%;
    background-color: #212121;
    line-height: 1.5em;
  }
  
  footer .image-container {
    width: 400px;
  }
  
  footer .content {
    flex-grow: 1;
    font-style: italic;
    color: #9b9b9b;
  }
  
  footer p {
    padding-bottom: 1.66rem;
  }
  
  footer p:last-child {
    padding-bottom: 0;
  }
  
  footer .author {
    color: #ffb78c;
  }
  
  footer em {
    color: #cfcfcf;
  }
  
  @media only screen and (max-width: 750px) {
    footer {
      flex-direction: column;
      padding: 0 10% 2rem 10%;
    }
  
    footer .image-container {
      height: 300px;
      margin-bottom: 2rem;
      overflow: hidden;
    }
  }
```