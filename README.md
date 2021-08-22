 HTML, CSS, and Git: Code Refactor Detail

I refactor the website (HTML and CSS code) to make it more accessible. 
I did some changes in HTML and CSS Code

Detail of following Changes are as follow:

1. I changed div to header tag and add nav tag in header section.
<header>, <nav>

2. I did internal link for functionality in HTML,

<div id="search-engine-optimization" class="search-engine-optimization">

3. I added img attributes in HTML, 

<img src="./assets/images/search-engine-optimization.jpg" alt="search-engine-optimization" class="float-left" />
<img src="./assets/images/online-reputation-management.jpg" alt="online-reputation-management" class="float-right" />
<img src="./assets/images/social-media-marketing.jpg" alt="social-media-marketing" class="float-left" />

<img src="./assets/images/lead-generation.png" alt="Lead Generation"/>
<img src="./assets/images/brand-awareness.png" alt="Brand Awareness"/>
<img src="./assets/images/cost-management.png" alt="Cost Management"/>

4. i changed div to footer tag.
<footer>

5. IN CSS CODE,


In condensing CSS Code, we applied:

6. I applied styles in header tag except of (.header) class selector 

7. I combined three selectors with same styles

.benefit-lead, .benefit-brand, .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-lead h3,
.benefit-brand h3,
.benefit-cost h3{
    margin-bottom: 10px;
    text-align: center;
}
.benefit-lead img,
.benefit-brand img,
.benefit-cost img{
    display: block;
    margin: 10px auto;
    max-width: 150px;

.search-engine-optimization,
.online-reputation-management,
.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.search-engine-optimization img,
.online-reputation-management img,
.social-media-marketing img {
    max-height: 200px; 
}

.search-engine-optimization h2,
.online-reputation-management h2,
.social-media-marketing h2{
    margin-bottom: 20px;
    font-size: 36px;
}


* I've added the connection links for functionality.

* I consolidated code in html and CSS.

* I deployed the application to url.

URL: https://github.com/Ruchi479/Refactor_Week1_Homework.git
