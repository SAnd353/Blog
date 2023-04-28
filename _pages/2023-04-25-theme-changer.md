---
title: Theme Changer
layout: base
---
# Theme Changer

<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="../assets/css/blackbg.css">
    <link rel="stylesheet" href="../assets/css/greenbg.css" id="theme-link">
</head>
<body>
    <button id="theme-toggle">Toggle Light/Dark Theme</button>
    <input id="bgpickerentry" placeholder="Pick a background color">
    <button id="bgpicker" onclick="changeBG()">Change</button>
    <script>
        const toggleButton = document.querySelector('#theme-toggle');
        const themeLink = document.querySelector('#theme-link');
        toggleButton.addEventListener('click', () => {
            if (themeLink.getAttribute('href') === '../assets/css/blackbg.css') {
                themeLink.setAttribute('href', '../assets/css/greenbg.css');
                document.body.style.background = '';
            } else {
                themeLink.setAttribute('href', '../assets/css/blackbg.css');
                document.body.style.background = '';
            }
        });
        function changeBG() {
            console.log(document.getElementById("bgpickerentry").innerText.toLowerCase())
            document.body.style.background = document.getElementById("bgpickerentry").value;
        }
    </script>
</body>
