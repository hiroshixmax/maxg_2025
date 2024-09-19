---
layout: base
title: Student Home
description: Home Page
hide: true
---

# **My journey starts here.**

<!-- Here's where I use JavaScript to put the image on my HomePage... -->
<div id="image-container"></div>

<script>
    // Create an image element
    const img = document.createElement('img');
    
    // Set the image source to the school logo
    img.src = 'https://delnorte.powayusd.com/pics/school_logo.png';
    
    // You can add other settings, like an alt text or size
    img.alt = 'Del Norte School Logo';
    img.width = 300; // Adjust this if needed

    // Add the image to the div with id "image-container"
    document.getElementById('image-container').appendChild(img);
</script>



### Visit my GitHub Blog

<br>

<style>
/* From Uiverse.io by TISEPSE */ 
    .btn2 {
        position: relative;
        display: inline-block;
        padding: 15px 30px;
        border: 2px solid #121212;
        text-transform: uppercase;
        color: #121212;
        text-decoration: none;
        font-weight: 600;
        font-size: 20px;
        transition: 0.3s;
    }

    .btn2::before {
        content: '';
        position: absolute;
        top: -2px;
        left: -2px;
        width: calc(100% + 4px);
        height: calc(100% - -2px);
        background-color: #88bc4c;
        transition: 0.3s ease-out;
        transform: scaleY(1);
    }

    .btn2::after {
        content: '';
        position: absolute;
        top: -2px;
        left: -2px;
        width: calc(100% + 4px);
        height: calc(100% - 50px);
        background-color: #88bc4c;
        transition: 0.3s ease-out;
        transform: scaleY(1);
    }

    .btn2:hover::before {
        transform: translateY(-25px);
        height: 0;
    }

    .btn2:hover::after {
        transform: scaleX(0);
        transition-delay: 0.15s;
    }

    .btn2:hover {
        border: 2px solid #121212;
    }

    .btn2 span {
        position: relative;
        z-index: 3;
    }

    button {
        text-decoration: none;
        border: none;
        background-color: transparent;
    }
</style>

<button>
  <a href="https://github.com/hiroshixmax/maxg_2025" class="btn2"><span class="spn2">Check my blog</span></a>
</button>



<style>
    .paste-button {
        position: relative;
        display: block;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    .button {
        background-color: #88bc4c;
        color: #ffffff;
        padding: 10px 15px;
        font-size: 15px;
        font-weight: bold;
        border: 2px solid transparent;
        border-radius: 15px;
        cursor: pointer;
    }

    .dropdown-content, .submenu-content {
        display: none;
        font-size: 13px;
        position: absolute;
        z-index: 1;
        min-width: 200px;
        background-color: #ffffff;
        border: 2px solid #88bc4c;
        border-radius: 0px 15px 15px 15px;
        box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    }

    .dropdown-content a, .submenu-content a {
        color: #88bc4c;
        padding: 8px 10px;
        text-decoration: none;
        display: block;
        transition: 0.1s;
    }

    .dropdown-content a:hover, .submenu-content a:hover {
        background-color: #88bc4c;
        color: #fff;
    }

    .dropdown-content a:focus, .submenu-content a:focus {
        background-color: #fff;
        color: #88bc4c;
    }

    .dropdown-content #top:hover {
        border-radius: 0px 13px 0px 0px;
    }

    .dropdown-content #bottom:hover {
        border-radius: 0px 0px 13px 13px;
    }

    .paste-button:hover button {
        border-radius: 15px 15px 0px 0px;
    }

    .paste-button:hover .dropdown-content {
        display: block;
    }

    /* Submenu styles */
    .submenu {
        position: relative;
    }

    .submenu-content {
        top: 0;
        left: 100%;
        border-radius: 0 15px 15px 15px;
    }

    .submenu-content a:first-child:hover {
        border-radius: 0px 13px 0px 0px;
    }

    .submenu-content a:last-child:hover {
        border-radius: 0px 0px 13px 13px;
    }

    .submenu:hover .submenu-content {
        display: block;
    }
</style>


<div class="paste-button">
  <button class="button">Menu &nbsp; ▼</button>
  <div class="dropdown-content">
    <a id="top" href="https://jasonguan1012.github.io/jgCSA_2025/devops/tools/home">JavaScript Hack</a>
    <div class="submenu">
        <a id="middle" href="https://jasonguan1012.github.io/jgCSA_2025/devops/2024/09/01/APCSAPlanning_IPYNB_2_.html">Planning Page &nbsp; ▶</a>
        <div class="submenu-content">
            <a href="https://jasonguan1012.github.io/jgCSA_2025/devops/2024/09/01/APCSAPlanning_IPYNB_2_.html">Goals, challenges, Accom.</a>
            <a href="https://jasonguan1012.github.io/jgCSA_2025/navigation/csa.html">Calendar</a>
        </div>
    </div>
    <a id="bottom" href="https://jasonguan1012.github.io/jgCSA_2025/about/">About Pages</a>
  </div>
</div>
