---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div class="content-wrapper">
    <h1> Welcome to My Portfolio </h1>
    <p>I'm William Leung, an aspiring software developer in Los Angeles, California. I love being practical and intuitive and always eager to learn new technologies to expand my repertoire. Welcome to my portfolio, where you can explore my projects and learn more about me.</p>
</div>

<div class="content-wrapper" id="about">
    <h1> About </h1>
    <div>
        <img src="/assets/images/william_leung.JPG" alt="William Leung Pic" style="width: 28%; height: auto; border-radius: 200px; float: right; margin: 10px">
    </div>
    <p style="text-align: justify;">
        I'm a Cal State LA computer science graduate passionate about developing practical and exciting applications. My journey into computer science began in high school with creating simple games in Scratch and Python. The joy of using my creativity and sharing my creations with friends sparked my passion for computer science.<br>
        <br>
        At Cal State LA, I explored various areas of software development, including databases, web development, and data science. I am proficient in Python, Java, and JavaScript, with hands-on experience using frameworks like Django, Flask, React-Native, and Express.js. My technical skills are complemented by a solid understanding of object-oriented programming, data structures, and algorithms.<br>
        <br>
        For my senior design project, I had the opportunity to work with The Aerospace Corporation. There, I gained industry experience with Docker containers, InfluxDB, and Python. I managed InfluxDB through Docker, efficiently formatted and processed data, and automated an internal satellite orbit analysis tool, significantly reducing analysis time. I also had the chance to brief aerospace customers on our project's outcomes.<br>
        <br>
        Beyond coding, I enjoy running and reading novels. I aspire to become a well-rounded developer, continuously leveraging my experience to create practical and helpful applications that can make a difference.
    </p>
</div>

<div class="content-wrapper" id="projects">
<h1> Projects </h1>

<p>
    I've tinkered on a lot of small and big projects over the years for school and personal purpose.<br> 
    These are the ones I'm most proud of.
</p>

<h2>Professional Projects:</h2>
<div class="projects-grid">
    <div class="project-card">
        <div class="project-image">
            <img src="/assets/images/aerospace_logo.jpg" alt="Aerospace Corp. Logo">
        </div>
        <div class="project-info">
            <h3>Automating Satellite Analysis with Containers</h3>
            <p>Automated analysis by leveraging container technology and an existing satellite orbit analysis tool developed at Aerospace that is normally used as a GUI</p>
        </div>
        <div class="tech-used">
            <h4>Technologies Used:</h4>
            <p>
                <!-- <img src="" alt=""> -->
                <img class="docker" style="border-radius: 5%">
                <img class="python">
                <img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=InfluxDB&logoColor=white" alt="InfluxDB">
            </p>
        </div>
    </div>
</div>


<h2>Personal Projects:</h2>
<div class="projects-grid">
    <div class="project-card">
        <div class="project-image">
            <img src="/assets/images/mangadex.png" alt="MangaDex Logo">
        </div>
        <div class="project-info">
            <h3>MangaDex React-native App</h3>
            <p>A manga reader built with React-native on Expo</p>
        </div>
        <div class="tech-used">
            <h4>Technologies Used:</h4>
            <p>
                <img class="javascript">
                <img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB" alt="react-native">
                <img src="https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37" alt="expo">
            </p>
        </div>
        <a class="github-button" href="https://github.com/willzerrs/Mangadex-App" target="_blank">View on GitHub</a>
    </div>
    <div class="project-card">
        <div class="project-image">
            <img src="/assets/images/jikan_logo.png" alt="Jikan API Logo">
        </div>
        <div class="project-info">
            <h3>Anime Title Search API</h3>
            <p>An Express.js server that retrieves anime information from MyAnimeList via JikanApi and stores search results into MongoDB.</p>
        </div>
        <div class="tech-used">
            <h4>Technologies Used:</h4>
            <p>
                <img class="javascript">
                <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="express-js">
                <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongo-db">
            </p>
        </div>
        <a class="github-button" href="https://github.com/willzerrs/Anime-Search-API" target="_blank">View on GitHub</a>
    </div>
    <div class="project-card">
        <div class="project-image">
            <img src="/assets/images/WL.png" alt="WL Logo" style="border-radius: 5px">
        </div>
        <div class="project-info">
            <h3>Personal Portfolio Website</h3>
            <p>A GitHub Pages portfolio website setup with Jekyll.</p>
        </div>
        <div class="tech-used">
            <h4>Technologies Used:</h4>
            <p>
                <img src="https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white" alt="ruby">
                <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="html">
                <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="css">
                <img src="https://camo.githubusercontent.com/ede395ad570a6b80bbcda5d08bdb5290668972442d5ab77b5460709071ebadc2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f706f776572656425323062792d4a656b796c6c2d626c75652e737667" alt="jekyll">
            </p>
        </div>
        <a class="github-button" href="https://github.com/willzerrs/willzerrs.github.io" target="_blank">View on GitHub</a>
    </div>
</div>
</div>