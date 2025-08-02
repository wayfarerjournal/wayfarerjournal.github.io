---
layout: about
title: About
permalink: /about/
---

<div class="about-layout">
  <div class="about-image">
    <img src="/assets/images/kyle-pasalskyj.jpg" alt="Kyle Pasalskyj">
  </div>
  
  <div class="about-content">
    <h1 class="about-heading">ABOUT ME</h1>
    <h2 class="about-name">KYLE PASALSKYJ - PHOTOGRAPHER</h2>
    
    <div class="about-text">
      <p>I'm a professional photographer with over a decade of experience in weddings, travel, and commercial photography.</p>
      
      <p>My path wasn't conventional. I spent a few years at university, studying both advertising and IT before realising it wasn't for me. The skills I picked up in that time would later prove invaluable, but I was eager to join the workforce and start learning from the people in it. I worked everything from wedding venues to web development, and even a very brief stint as a door-to-door salesman, before discovering my passion for photography. What started as morning photo walks and freelance shoots eventually grew into a full-time career, capturing 30 to 50 weddings a year.</p>
      
      <p>In 2017, a solo photography trip to New Zealand changed everything. My travel photography gained international recognition, being featured by Apple, Condé Nast, and BuzzFeed. This led to becoming a Sony Digital Imaging Advocate and representing the brand on a month-long expedition to Antarctica.</p>
      
      <p>After returning from Antarctica, I shifted my attention away from travel and weddings, and decided to work harder at being a more present husband and father. I took up a role as Creative Director at a leading property photography studio, where I now help guide the creative output of a team of photographers.</p>
      
      <p><em>Wayfarer Journal</em> is where I return to the kind of storytelling that first drew me to photography. Slower, and deeply personal. I want to tell the stories of amazing people doing amazing things.</p>
      
      <p>Wayfarer Journal is my love letter to stories. To the golden age of reportage. To the simple pleasure of a good story.</p>
      
      <p>This is a version of events. Cherished, missed, loud, quiet, fact, and fiction.</p>
      
      <p>It's an outsider's perspective. An interpretation of the mundane.</p>
      
      <p>It's a collection of connections. A public record of "This is who we were. This is what we did. This is why it mattered."</p>
      
      <p>When I'm not behind the camera, I'm usually exploring somewhere new with my wife Selena and our two sons, Noah and Eddie, tinkering with web projects, or sharing what I've learnt with other photographers.</p>
    </div>
  </div>
</div>

<style>
  .about-layout {
    display: flex;
    gap: 80px;
    max-width: 1200px;
    margin: 0 auto;
    padding: 60px 20px;
    min-height: 80vh;
    align-items: flex-start;
  }
  
  .about-image {
    flex: 0 0 45%;
  }
  
  .about-image img {
    width: 100%;
    height: auto;
    object-fit: cover;
    border-radius: 8px;
  }
  
  .about-content {
    flex: 1;
  }
  
  .about-heading {
    font-family: var(--heading-font) !important;
    font-size: 3rem !important;
    font-weight: 400 !important;
    color: #333 !important;
    margin-bottom: 10px !important;
    text-transform: uppercase !important;
    letter-spacing: 2px !important;
  }
  
  .about-name {
    font-family: var(--nav-font) !important;
    font-size: 1.2rem !important;
    font-weight: 500 !important;
    color: #ed1c24 !important;
    margin-bottom: 40px !important;
    text-transform: uppercase !important;
    letter-spacing: 1px !important;
  }
  
  .about-text {
    font-family: var(--body-font) !important;
    font-size: 1.1rem !important;
    line-height: 1.8 !important;
    color: #555 !important;
  }
  
  .about-text p {
    margin-bottom: 20px !important;
  }
  
  .about-text p:last-child {
    margin-bottom: 0 !important;
  }
  
  @media (max-width: 768px) {
    .about-layout {
      flex-direction: column;
      gap: 40px;
      padding: 40px 20px;
    }
    
    .about-image {
      flex: none;
      width: 100%;
    }
    
    .about-heading {
      font-size: 2.5rem !important;
    }
    
    .about-name {
      font-size: 1rem !important;
      margin-bottom: 30px !important;
    }
  }
</style> 