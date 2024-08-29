<script>
</script>

<style>
    .about-header {
        text-align: center;
        color: goldenrod; 
    }
    .about-header h1 {
        font-size: 1.5em;
    }
    .about-header h2 {
        font-size: 1.2em;
    }
    .about-description {
        text-align: center;
        padding: 20px;
    }
    .values-section {
        display: flex;
        justify-content: space-around;
        padding: 20px;
        flex-wrap: wrap;
    }
    .value-box {
        width: 30%;
        padding: 20px;
        border: 1px solid gainsboro;
        text-align: center;
        background-color: whitesmoke;
        margin: 10px;
        box-sizing: border-box;
    }
    .value-box h3 {
        color: darkblue; 
        font-size: 1.2em;
        margin-bottom: 10px;
    }
    .value-box p {
        font-size: 0.9em;
    }
    .core-values {
        display: flex;
        justify-content: center;
        gap: 10px;
        flex-wrap: wrap;
        margin: 20px 0;
    }
    .core-values div {
        padding: 10px 20px;
        background-color: darkblue; 
        color: white;
        font-size: 0.9em;
        text-align: center;
        border-radius: 5px;
    }
    .mission-statement {
        text-align: center;
        padding: 20px;
        font-weight: bold;
        font-size: 1.2em;
    }
    .image-section {
        text-align: center;
        margin-top: 20px;
    }
    .image-section img {
        width: 55%;
        height: auto;
    }
    .support-section {
        text-align: center;
        margin-top: 30px;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .support-input {
        width: 100%;
        max-width: 600px;
        padding: 10px;
        font-size: 1em;
        border: 1px solid silver;
        border-radius: 5px;
        margin-bottom: 10px;
    }
    .support-button {
        width: 100%;
        max-width: 600px;
        padding: 15px;
        background: linear-gradient(to right, lemonchiffon, goldenrod);
        border: none;
        color: white;
        font-size: 1.2em;
        text-align: center;
        border-radius: 5px;
        cursor: pointer;
    }
    .support-button:hover {
        background: linear-gradient(to right, goldenrod, lemonchiffon);
    }
    @media (max-width: 768px) {
        .value-box {
            width: 100%;
        }
        .support-input, .support-button {
            width: 90%;
        }
    }
</style>

<div class="about-header">
    <h1>About SoWhereTo &gt; Access</h1>
    <h2>Unveil the Unseen: Access African Quality</h2>
</div>

<div class="about-description">
    <p>Leading digital innovation as a platform for economic change in Africa. Supporting local brands to showcase exclusive high-quality creations for global appreciation of cultural richness. Curated in the spirit of crafting a new African narrative for generational wealth and success.</p>
</div>

<div class="values-section">
    <div class="value-box">
        <h3>Explore</h3>
        <p>A world where visionary local brands showcase exclusive creations. Step into the realm of unparalleled finds that will thrust you to the forefront of innovation. Be part of reimagining a new African story!</p>
    </div>
    <div class="value-box">
        <h3>Mission</h3>
        <p>Our mission is to provide a marketplace that celebrates and advances African entrepreneurship, creativity, and skills, ensuring our offerings are distinctive and forward-thinking, at international standards.</p>
    </div>
    <div class="value-box">
        <h3>Vision</h3>
        <p>We are dedicated to sourcing and offering products and solutions that reflect our values of quality, uniqueness, and cultural richness.</p>
    </div>
</div>
<div style="display: flex; justify-content: center;">
    <iframe width="600" height="400" src="https://www.youtube.com/embed/5vUZVVJVkow" 
        title="AMS#transformationtuesday" frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
    </iframe>
</div>

<div class="support-section">
    <input type="text" class="support-input" placeholder="Support" value="R">
    <button class="support-button">SUPPORT SA APP</button>
</div>

<div class="core-values">
    <div>PASSION</div>
    <div>INNOVATION</div>
    <div>GLOBAL CONNECTION</div>
    <div>SOCIAL IMPACT</div>
    <div>SKILLS DEVELOPMENT</div>
    <div>CREATIVITY</div>
</div>

<div class="mission-statement">
    <p>AMS AIMS TO NOT ONLY HELP BUSINESSES GROW BUT TO ALSO MAKE A POSITIVE IMPACT ON SOCIETY BY NURTURING LOCAL TALENT AND FOSTERING SUSTAINABLE BUSINESS GROWTH.</p>
</div>

<div class="image-section">
     <img src="lion-wall-art.jpg" alt="Lion Image">
</div>
