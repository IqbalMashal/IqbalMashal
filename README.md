To create a pop-up animation effect for your name and add icons for React, Express.js, and Next.js, you can use CSS animations along with your existing HTML structure. Below is an updated version of your code that includes these enhancements.

### Updated HTML with CSS Animation

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f8ff; /* Light blue background */
            text-align: center;
        }

        .popup {
            display: inline-block;
            animation: pop 0.5s ease-in-out;
        }

        @keyframes pop {
            0% {
                transform: scale(0);
                opacity: 0;
            }
            50% {
                transform: scale(1.1);
                opacity: 1;
            }
            100% {
                transform: scale(1);
            }
        }

        .heading {
            font-size: 50px;
            font-weight: bold;
            border-bottom: 5px solid #007bff; /* Darker blue for contrast */
            color: #007bff; /* Darker blue text */
            padding: 20px;
        }

        .footer {
            font-size: 20px;
            font-weight: normal;
            border-top: 5px solid #007bff; /* Darker blue for contrast */
            color: #007bff; /* Darker blue text */
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .languages {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .languages img {
            margin: 10px;
        }
    </style>
</head>
<body>

<h1 class="popup">Hi 👋, I'm Iqbal Mashal</h1>
<h3>A passionate software developer from Canada</h3>

<div>
    <img src="https://github-readme-stats.vercel.app/api?username=iqbalmashal&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="150" alt="stats graph" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=iqbalmashal&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph" />
</div>

<div>
    <img height="200" src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" />
</div>

<h3 align="left">Languages and Tools:</h3>
<p class="languages">
    <a href="https://reactjs.org/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="react" width="40" height="40"/>
    </a>
    <a href="https://expressjs.com/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg" alt="express" width="40" height="40"/>
    </a>
    <a href="https://nextjs.org/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" alt="nextjs" width="40" height="40"/>
    </a>
    <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/>
    </a>
    <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/>
    </a>
    <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3
