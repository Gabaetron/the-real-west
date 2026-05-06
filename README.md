<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Who Were the First Cowboys?</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Source+Serif+4:wght@300;400;600&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
 
    body {
      font-family: 'Source Serif 4', serif;
      background-color: #faf9f6;
      color: #1a1a1a;
      min-height: 100vh;
    }
 
    .site {
      max-width: 860px;
      margin: 0 auto;
      padding: 0 1.5rem 4rem;
    }
 
    .hero {
      text-align: center;
      padding: 4rem 1rem 3rem;
      border-bottom: 1px solid #e0ddd6;
      margin-bottom: 2.5rem;
    }
 
    .hero-eyebrow {
      font-size: 12px;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      color: #888;
      margin-bottom: 1rem;
    }
 
    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: 42px;
      font-weight: 700;
      line-height: 1.15;
      margin-bottom: 1rem;
      color: #1a1a1a;
    }
 
    .hero p {
      font-size: 17px;
      color: #555;
      max-width: 600px;
      margin: 0 auto;
      line-height: 1.7;
    }
 
    .nav {
      display: flex;
      gap: 8px;
      justify-content: center;
      flex-wrap: wrap;
      margin-bottom: 2.5rem;
    }
 
    .nav-btn {
      background: transparent;
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 8px 18px;
      font-family: 'Source Serif 4', serif;
      font-size: 14px;
      color: #555;
      cursor: pointer;
      transition: all 0.15s;
    }
 
    .nav-btn:hover, .nav-btn.active {
      background: #f0ede6;
      color: #1a1a1a;
      border-color: #999;
    }
 
    .section { display: none; }
    .section.active { display: block; }
 
    .section-title {
      font-family: 'Playfair Display', serif;
      font-size: 28px;
      font-weight: 700;
      margin-bottom: 0.5rem;
      color: #1a1a1a;
    }
 
    .section-sub {
      font-size: 15px;
      color: #555;
      margin-bottom: 2rem;
      line-height: 1.6;
    }
 
    .card-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 1rem;
      margin-bottom: 2rem;
    }
 
    .card {
      background: #fff;
      border: 1px solid #e0ddd6;
      border-radius: 12px;
      padding: 1.25rem;
    }
 
    .card-label {
      font-size: 11px;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: #aaa;
      margin-bottom: 0.5rem;
    }
 
    .card h3 {
      font-family: 'Playfair Display', serif;
      font-size: 18px;
      font-weight: 400;
      margin-bottom: 0.75rem;
      color: #1a1a1a;
    }
 
    .card p {
      font-size: 14px;
      color: #555;
      line-height: 1.65;
    }
 
    .timeline {
      position: relative;
      padding-left: 2rem;
    }
 
    .timeline::before {
      content: '';
      position: absolute;
      left: 0;
      top: 0;
      bottom: 0;
      width: 1px;
      background: #e0ddd6;
    }
 
    .timeline-item {
      position: relative;
      margin-bottom: 2rem;
    }
 
    .timeline-dot {
      position: absolute;
      left: -2.4rem;
      top: 4px;
      width: 10px;
      height: 10px;
      border-radius: 50%;
      background: #faf9f6;
      border: 2px solid #999;
    }
 
    .timeline-date {
      font-size: 12px;
      letter-spacing: 0.08em;
      color: #aaa;
      margin-bottom: 0.25rem;
    }
 
    .timeline-title {
      font-family: 'Playfair Display', serif;
      font-size: 17px;
      margin-bottom: 0.4rem;
      color: #1a1a1a;
    }
 
    .timeline-text {
      font-size: 14px;
      color: #555;
      line-height: 1.65;
    }
 
    .quote-block {
      border-left: 2px solid #999;
      padding: 1rem 1.5rem;
      margin: 1.5rem 0;
    }
 
    .quote-text {
      font-size: 17px;
      font-style: italic;
      line-height: 1.7;
      color: #1a1a1a;
      margin-bottom: 0.5rem;
    }
 
    .quote-attr {
      font-size: 13px;
      color: #888;
    }
 
    .stat-row {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      margin-bottom: 2rem;
    }
 
    .stat {
      background: #f0ede6;
      border-radius: 8px;
      padding: 1rem 1.25rem;
      flex: 1;
      min-width: 140px;
    }
 
    .stat-num {
      font-family: 'Playfair Display', serif;
      font-size: 28px;
      margin-bottom: 0.25rem;
      color: #1a1a1a;
    }
 
    .stat-label {
      font-size: 13px;
      color: #666;
      line-height: 1.4;
    }
 
    .profile-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
 
    .profile {
      background: #fff;
      border: 1px solid #e0ddd6;
      border-radius: 12px;
      padding: 1.25rem;
    }
 
    .profile-initial {
      width: 44px;
      height: 44px;
      border-radius: 50%;
      background: #ddeaf7;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 500;
      font-size: 16px;
      color: #2a5f9e;
      margin-bottom: 1rem;
    }
 
    .profile h3 {
      font-family: 'Playfair Display', serif;
      font-size: 16px;
      font-weight: 400;
      margin-bottom: 0.25rem;
      color: #1a1a1a;
    }
 
    .profile-role {
      font-size: 12px;
      color: #aaa;
      margin-bottom: 0.75rem;
    }
 
    .profile p {
      font-size: 13px;
      color: #555;
      line-height: 1.6;
    }
 
    .sources-list { list-style: none; }
 
    .sources-list li {
      padding: 1rem 0;
      border-bottom: 1px solid #e0ddd6;
      font-size: 14px;
      color: #555;
      line-height: 1.6;
    }
 
    .sources-list li:last-child { border-bottom: none; }
 
    .source-title {
      color: #1a1a1a;
      font-style: italic;
    }
 
    footer {
      text-align: center;
      padding: 2rem 0 1rem;
      font-size: 13px;
      color: #aaa;
      border-top: 1px solid #e0ddd6;
      margin-top: 3rem;
    }
 
    @media (max-width: 600px) {
      .hero h1 { font-size: 30px; }
      .stat-row { flex-direction: column; }
    }
  </style>
</head>
<body>
  <div class="site">
    <div class="hero">
      <p class="hero-eyebrow">American History</p>
      <h1>Who Were the First Cowboys?</h1>
      <p>The real history of the American cowboy looks nothing like Hollywood. Explore the Indigenous, Mexican, and African American origins of cowboy culture.</p>
    </div>
 
    <div class="nav">
      <button class="nav-btn active" onclick="show('overview', this)">Overview</button>
      <button class="nav-btn" onclick="show('vaqueros', this)">Vaqueros</button>
      <button class="nav-btn" onclick="show('black-cowboys', this)">African American cowboys</button>
      <button class="nav-btn" onclick="show('timeline', this)">Timeline</button>
      <button class="nav-btn" onclick="show('profiles', this)">Notable figures</button>
      <button class="nav-btn" onclick="show('sources', this)">Sources</button>
    </div>
 
    <div id="overview" class="section active">
      <p class="section-title">The myth vs. the reality</p>
      <p class="section-sub">For generations, popular culture has portrayed the American cowboy as a white man riding the open range. The historical record tells a very different story.</p>
 
      <div class="stat-row">
        <div class="stat">
          <div class="stat-num">1 in 3</div>
          <div class="stat-label">Cowboys in the late 1800s were Mexican vaqueros</div>
        </div>
        <div class="stat">
          <div class="stat-num">1 in 4</div>
          <div class="stat-label">Cowboys on the trails were African American</div>
        </div>
        <div class="stat">
          <div class="stat-num">1519</div>
          <div class="stat-label">Year Spanish settlers first trained Indigenous vaqueros in Mexico</div>
        </div>
        <div class="stat">
          <div class="stat-num">1000s</div>
          <div class="stat-label">Estimated enslaved African American cowboys in Texas before the Civil War</div>
        </div>
      </div>
 
      <div class="card-grid">
        <div class="card">
          <div class="card-label">Origin</div>
          <h3>The vaquero tradition</h3>
          <p>Hundreds of years before the American cowboy, Indigenous Mesoamerican men trained by Spanish settlers were herding cattle across what is now Mexico, Texas, Arizona, and California.</p>
        </div>
        <div class="card">
          <div class="card-label">Erasure</div>
          <h3>Written out of history</h3>
          <p>Dime store novels, Wild West shows, and Hollywood films systematically replaced the real, multicultural cowboy with a romanticized white hero. Historians have called this a process of deliberate mythologization.</p>
        </div>
        <div class="card">
          <div class="card-label">Reality</div>
          <h3>A multicultural workforce</h3>
          <p>The cattle industry was built by Indigenous people, Mexican vaqueros, enslaved African Americans, and freed African American men working together on ranches and trail drives across the American West.</p>
        </div>
      </div>
 
      <div class="quote-block">
        <p class="quote-text">"All of the skills, traditions, and ways of working with cattle are very much rooted in the Mexican vaquero. If you are a cowboy in the U.S. today, you have developed what you know from the vaquero."</p>
        <p class="quote-attr">Kendall Nelson, photographer and cowboy historian</p>
      </div>
    </div>
 
    <div id="vaqueros" class="section">
      <p class="section-title">The vaquero tradition</p>
      <p class="section-sub">The word "vaquero" comes from the Spanish word vaca, meaning cow. These were the world's first cowboys: skilled, proud, and largely forgotten by mainstream history.</p>
 
      <div class="card-grid">
        <div class="card">
          <div class="card-label">Who they were</div>
          <h3>Indigenous and mestizo men</h3>
          <p>The original vaqueros were largely Indigenous Mesoamerican men trained by Spanish missionaries beginning in 1519. Over time, mestizos, men of mixed Spanish and Indigenous heritage, joined their ranks.</p>
        </div>
        <div class="card">
          <div class="card-label">What they invented</div>
          <h3>The tools of cowboy culture</h3>
          <p>Vaqueros invented or perfected the lasso, chaps, the western saddle, and the techniques of horse taming and cattle roping. Every tool associated with the American cowboy traces directly to vaquero culture.</p>
        </div>
        <div class="card">
          <div class="card-label">Their reach</div>
          <h3>From Mexico to California</h3>
          <p>As Spain expanded its empire westward, vaqueros spread from central Mexico through Texas, New Mexico, Arizona, and into California, establishing ranching cultures that white settlers would later inherit.</p>
        </div>
      </div>
 
      <div class="quote-block">
        <p class="quote-text">"It's a forgotten history of centuries of horsemanship in the Americas that root the vaqueros to the colonial past."</p>
        <p class="quote-attr">Pablo A. Rangel, independent historian</p>
      </div>
 
      <div class="card" style="margin-top: 1rem;">
        <div class="card-label">The caballero and the vaquero</div>
        <h3>A class distinction</h3>
        <p>A caballero was a gentleman on horseback and the wealthy ranch owner. A vaquero was a worker on horseback who did the actual cattle work. The caballero owned the land and the vaquero worked it. Despite their lower social status, vaqueros were extraordinarily skilled and deeply proud of their craft.</p>
      </div>
    </div>
 
    <div id="black-cowboys" class="section">
      <p class="section-title">African American cowboys</p>
      <p class="section-sub">Enslaved African Americans in Texas were doing skilled cowboy work as early as the 1820s and 1830s, decades before the Civil War and long before the image of the cowboy entered popular culture.</p>
 
      <div class="stat-row">
        <div class="stat">
          <div class="stat-num">2.76M</div>
          <div class="stat-label">Cattle in Texas by 1860, requiring thousands of cowboys</div>
        </div>
        <div class="stat">
          <div class="stat-num">35,000</div>
          <div class="stat-label">Estimated total cowboys on the western frontier</div>
        </div>
        <div class="stat">
          <div class="stat-num">5,000+</div>
          <div class="stat-label">Estimated African American cowboys in the late 19th century</div>
        </div>
      </div>
 
      <div class="quote-block">
        <p class="quote-text">"It is likely that there were hundreds, if not thousands, of enslaved cowboys in Texas."</p>
        <p class="quote-attr">Kyle Ainsworth, Journal of Southern History, 2020</p>
      </div>
 
      <div class="card-grid">
        <div class="card">
          <div class="card-label">Before emancipation</div>
          <h3>Enslaved cowboys</h3>
          <p>Enslaved African Americans on Texas ranches and plantations were trained in cattle herding, horse breaking, and roping. They often learned directly from Mexican vaqueros and were doing skilled cowboy work long before the Civil War ended.</p>
        </div>
        <div class="card">
          <div class="card-label">After emancipation</div>
          <h3>Free African American cowboys</h3>
          <p>Following the Civil War, thousands of formerly enslaved people continued working as cowboys. The West offered far greater opportunities for dignity and livelihoods than the post-Reconstruction South.</p>
        </div>
        <div class="card">
          <div class="card-label">Their erasure</div>
          <h3>Written out of the story</h3>
          <p>Publishers, film studios, and dime novel writers systematically excluded African American cowboys from their stories to appeal to white audiences. This process of erasure continued well into the 20th century.</p>
        </div>
      </div>
    </div>
 
    <div id="timeline" class="section">
      <p class="section-title">A timeline of cowboy origins</p>
      <p class="section-sub">The history of the cowboy spans five centuries and three continents.</p>
 
      <div class="timeline">
        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <p class="timeline-date">1519</p>
          <p class="timeline-title">Spanish arrive in Mexico</p>
          <p class="timeline-text">Spanish conquistadors arrive in what is now Mexico, bringing cattle and horses. They begin training Indigenous Mesoamerican men to herd cattle on horseback, marking the birth of the vaquero tradition.</p>
        </div>
        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <p class="timeline-date">1598</p>
          <p class="timeline-title">Don Juan de Oñate's expedition</p>
          <p class="timeline-text">One of the richest men in New Spain leads an expedition across the Rio Grande into present-day New Mexico, bringing approximately 7,000 animals. Vaqueros have now been perfecting their craft for nearly 80 years.</p>
        </div>
        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <p class="timeline-date">1821</p>
          <p class="timeline-title">White settlers arrive in Texas</p>
          <p class="timeline-text">Led by Stephen F. Austin, white settlers arrive in Texas and encounter millions of longhorn cattle roaming free, cattle the vaqueros had been managing for over 200 years. Many settlers bring enslaved people with them.</p>
        </div>
        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <p class="timeline-date">1830s–1860s</p>
          <p class="timeline-title">Enslaved African American cowboys in Texas</p>
          <p class="timeline-text">Enslaved African Americans on Texas ranches and plantations are trained as cowboys, learning from vaqueros and white ranchers. By 1860 Texas has over 2.76 million cattle, requiring thousands of cowboys, many of them enslaved.</p>
        </div>
        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <p class="timeline-date">1865</p>
          <p class="timeline-title">Emancipation and the cattle drives</p>
          <p class="timeline-text">The Civil War ends. Thousands of formerly enslaved African American cowboys continue their work, riding the great cattle trails north from Texas. Historians estimate up to 25% of all trail cowboys were African American.</p>
        </div>
        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <p class="timeline-date">1870s–1880s</p>
          <p class="timeline-title">The heyday of the cattle drives</p>
          <p class="timeline-text">The height of the open range cattle era. Cowboys of all backgrounds, African American, Mexican, Indigenous, and white, ride the Chisholm, Goodnight-Loving, and other major trails. One in three cowboys is a Mexican vaquero.</p>
        </div>
        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <p class="timeline-date">1880s–1900s</p>
          <p class="timeline-title">The myth takes shape</p>
          <p class="timeline-text">Barbed wire ends the open range era. Dime novels and Wild West shows begin constructing the myth of the white cowboy, systematically erasing the African American and Mexican cowboys who built the industry.</p>
        </div>
        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <p class="timeline-date">20th century</p>
          <p class="timeline-title">Hollywood cements the myth</p>
          <p class="timeline-text">Film and television complete the erasure. The American cowboy becomes a white icon of nationalism and individualism, a mythology built on centuries of forgotten African American and Mexican labor.</p>
        </div>
      </div>
    </div>
 
    <div id="profiles" class="section">
      <p class="section-title">Notable figures</p>
      <p class="section-sub">Real cowboys whose stories were buried by popular mythology.</p>
 
      <div class="profile-grid">
        <div class="profile">
          <div class="profile-initial">NL</div>
          <h3>Nat Love</h3>
          <p class="profile-role">Born enslaved, Tennessee, 1854</p>
          <p>Headed west at age 14 after emancipation. Became one of the most celebrated African American cowboys on the frontier, working cattle drives across Texas, Arizona, and the Great Plains.</p>
        </div>
        <div class="profile">
          <div class="profile-initial">BI</div>
          <h3>Bose Ikard</h3>
          <p class="profile-role">Born enslaved, Mississippi, 1847</p>
          <p>Rode with Charles Goodnight on the famous Goodnight-Loving Trail. Goodnight trusted Ikard above all others, often entrusting him to carry large sums of money at the end of cattle drives.</p>
        </div>
        <div class="profile">
          <div class="profile-initial">BP</div>
          <h3>Bill Pickett</h3>
          <p class="profile-role">Born in Texas, 1871</p>
          <p>Invented the rodeo event of bulldogging, wrestling steers to the ground. Became a world champion rodeo performer and international star, touring England, Canada, and South America.</p>
        </div>
        <div class="profile">
          <div class="profile-initial">GM</div>
          <h3>George McJunkin</h3>
          <p class="profile-role">Born enslaved, Texas, c. 1851</p>
          <p>Rose from wrangler to ranch manager in New Mexico. In 1908 discovered ancient bones in an arroyo that led to an archaeological find proving human existence in North America 10,000 years ago.</p>
        </div>
        <div class="profile">
          <div class="profile-initial">JO</div>
          <h3>Don Juan de Oñate</h3>
          <p class="profile-role">New Spain, 1550–1626</p>
          <p>Among the first cowboys in what is now the United States. Led a major expedition across the Rio Grande in 1598, bringing thousands of animals and establishing the vaquero tradition in the American Southwest.</p>
        </div>
        <div class="profile">
          <div class="profile-initial">SW</div>
          <h3>Sam Jones Washington</h3>
          <p class="profile-role">Born enslaved, Texas, c. 1849</p>
          <p>Began working with cattle at age fifteen while still enslaved. His WPA testimony, "I's never skeert w'en I's roundin' de cattle, 'cause I's sho ob my ridin'," is among the most direct firsthand accounts of an enslaved cowboy.</p>
        </div>
      </div>
    </div>
 
    <div id="sources" class="section">
      <p class="section-title">Sources</p>
      <p class="section-sub">This website draws on the following scholarly and credible sources.</p>
 
      <ul class="sources-list">
        <li>Ainsworth, Kyle. <span class="source-title">"Field Hands, Cowboys, and Runaways: Enslaved People on Horseback in Texas's Planter-Herder Economy, 1835–1865."</span> The Journal of Southern History, vol. 86, no. 3, August 2020, pp. 557–600.</li>
        <li>Goldstein-Shirley, David. <span class="source-title">"African American Cowboys in the American West: An Historiographical Review."</span> Ethnic Studies Review, vol. 20, 1997, p. 6.</li>
        <li>Hardaway, Roger D. <span class="source-title">"African American Cowboys on the Western Frontier."</span> Negro History Bulletin, vol. 64, no. 1–4, 2001, pp. 27–32.</li>
        <li>Gandhi, Lakshmi. <span class="source-title">"How Mexican Vaqueros Inspired the American Cowboy."</span> History.com, A&E Television Networks, 24 Sept. 2021.</li>
        <li>Haeber, Jonathan. <span class="source-title">"Vaqueros: The First Cowboys of the Open Range."</span> National Geographic, 15 Aug. 2003.</li>
        <li><span class="source-title">"The Evolution of Cowboy Culture."</span> Sid Richardson Museum, 18 Aug. 2021.</li>
      </ul>
    </div>
 
    <footer>
      <p>Created for academic research purposes. All content based on cited scholarly and credible sources.</p>
    </footer>
  </div>
 
  <script>
    function show(id, btn) {
      document.querySelectorAll('.section').forEach(s => s.classList.remove('active'));
      document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('active'));
      document.getElementById(id).classList.add('active');
      btn.classList.add('active');
    }
  </script>
</body>
</html>
