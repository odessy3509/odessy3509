# Portfolio

## 🌟 Banner
![Banner](https://github.com/odessy3509/odessy3509/assets/137520021/eb6ccd55-9351-4e17-9c3a-ff6d69d6584c)

---

## ✨ Introduction
It's fantastic to connect with a passionate creator like you! I share your enthusiasm for creating engaging games.  
My expertise lies in **C#**, **Unity**, and **2D and pixel art**, making us a great team to bring exciting projects to life.  
I'm eager to collaborate and combine our skills to craft immersive and enjoyable gaming experiences.  
Let's embark on this creative journey together and build some extraordinary games! 🚀

---

## 🎮 Current Work
- **Small Games:** Currently working on developing a variety of small, entertaining games.
- **Game Jams:** Actively participating in Game Jams to explore creativity and accelerate game development skills.
- **Indie Studio:** Engaged with a small but rapidly growing indie studio, contributing to exciting projects.

---

## 📊 Stats
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=odessy3509&show_icons=true&theme=radical)  
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=odessy3509&theme=radical)

---

## 📬 Contact
- **Email:** [odessy3509@gmail.com](mailto:odessy3509@gmail.com)
- **Discord:** [Join the Server!](https://discord.com/invite/example)
- **Itch.io:** [odessy.itch.io](https://odessy.itch.io)

---

## 🎨 My Artwork
![Miata 1](https://github.com/user-attachments/assets/9b0cc134-15ea-4c76-b2fb-bbacb1b79fde)  
![Miata 2](https://github.com/user-attachments/assets/d6423fcb-55d3-4018-a318-db9633cb1d1e)

---

## ✨ Animations & Assets
![PlayerIdle](https://github.com/odessy3509/odessy3509/assets/137520021/259d3031-bd33-47c2-92ad-b3397c347945)  
![Wendigo](https://github.com/odessy3509/odessy3509/assets/137520021/2906003f-cdfd-4d80-982f-5871e9f6f890)

---

## 🎥 GIF Previews
![GIF 1](https://i.gyazo.com/421be63b9f0484e2b3e091f1a305066f.gif)  
![GIF 2](https://i.gyazo.com/87f5f89b6c8015dc8fb44e504d0a234e.gif)  
![GIF 3](https://i.gyazo.com/9406abee664760b76d9ac888a309dcb6.gif)

---

## ❤️ Support
If you enjoy my work and would like to support me, consider buying me a coffee!  
[![Support Me on Ko-Fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/odessy)

/* General Body Styling */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #0d1117; /* Dark background */
  color: #c9d1d9; /* Light text */
  margin: 0;
  padding: 20px;
}

/* Main Container */
.github-readme {
  max-width: 900px;
  margin: auto;
  padding: 20px;
  background: #161b22; /* Slightly lighter dark background */
  border: 1px solid #30363d; /* Subtle border */
  border-radius: 6px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.3);
}

/* Header Styling */
h2 {
  color: #ffffff; /* Bright blue for headings */
  border-bottom: 2px solid #30363d;
  padding-bottom: 5px;
  text-align: left; /* Keep headers left-aligned */
}


  /* Styles for the copy feedback */
.copy-feedback {
  position: fixed;
  bottom: 50px;
  left: 50%;
  transform: translate(-50%, 30px); /* Center horizontally and add slight vertical offset */
  background-color: #161b22; 
  color: white;
  padding: 10px 15px;
  border-radius: 5px;
  font-size: 14px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
  opacity: 0;
  transition: opacity 0.3s, transform 0.3s;
  z-index: 1000;
}

.copy-feedback.visible {
  opacity: 1;
  transform: translate(-50%, 0); /* Center horizontally and remove vertical offset */
}

  

/* Links */
a {
  color: #58a6ff;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* Lists */
ul {
  padding-left: 20px;
}

ul li {
  margin-bottom: 10px;
}

/* Stats Container */
.stats {
  display: flex; /* Align images side by side */
  gap: 15px; /* Space between the images */
  justify-content: center; /* Center the entire stats section */
  align-items: stretch; /* Make images align evenly in height */
}

/* Stat Images */
.stats img {
  width: auto; /* Maintain the image's natural width */
  height: 180px; /* Set a fixed height */
  border-radius: 6px; /* Add rounded corners */
  border: 1px solid #30363d; /* Border styling */
  background: #0d1117; /* Add a background color behind images */
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.6); /* Optional shadow */
  object-fit: contain; /* Maintain aspect ratio inside the height limit */
}

/* Artwork Section */
.artwork {
  display: flex; /* Align the boxes horizontally */
  gap: 20px; /* Space between the boxes */
  justify-content: center; /* Center the boxes on the page */
  flex-wrap: wrap; /* Allow wrapping to the next row if necessary */
  margin: 20px 0;
}

/* Individual Boxes */
.artwork .box {
  width: 300px; /* Fixed width for consistency */
  height: 300px; /* Fixed height for consistency */
  background: #161b22; /* Box background color */
  border-radius: 6px; /* Rounded corners */
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.6); /* Subtle shadow for depth */
  border: 2px solid #30363d; /* Thicker border for uniform outline */
  overflow: hidden; /* Prevent content overflow */
  display: flex; /* Enable centering of content */
  justify-content: center; /* Center image horizontally */
  align-items: center; /* Center image vertically */
  position: relative; /* For any future inner elements */
}

/* Artwork and Animations Container */
.artwork,
.animations {
  display: flex;
  flex-wrap: wrap; /* Allow items to wrap if there's not enough space */
  gap: 10px; /* Adds spacing between boxes */
  justify-content: center; /* Optional: center the boxes */
}

/* Images (Artwork & Animations) */
.artwork img,
.animations img {
  width: auto; /* Maintain the natural width of the image */
  height: 100%; /* Scale to fit the height of the box */
  max-height: 250px; /* Set the maximum height */
  margin: 10px;
  border-radius: 6px;
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.6);
  border: 1px solid #30363d;
  background: #161b22;
  object-fit: contain; /* Ensures the image is contained within its box without distortion */
}

/* Add Outline on Hover */
.artwork .box:hover {
  border-color: #f1c40f; /* Change border color on hover */
  transform: scale(1.05); /* Slightly enlarge the box on hover */
  transition: transform 0.3s ease, border-color 0.3s ease;
}




/* Support Section */
.support {
  text-align: center;
  margin-top: 20px;
}
/* Contact section container */
.contact {
  display: flex;
  justify-content: center; /* Centers the items horizontally */
  gap: 20px; /* Space between each item */
}

/* Contact button (link + text box) */
.contact-button {
  display: flex;
  align-items: center;
  justify-content: center; /* Centers the content inside the button */
  padding: 10px 20px;
  border-radius: 8px;
  border: 2px solid #000000; /* Light grey border for the button */
  text-decoration: none; /* Removes the underline from the link */
  color: #fff; /*main text */
  font-weight: bold;
  transition: background 0.3s ease, transform 0.3s ease, border-color 0.3s ease;
  gap: 10px; /* Space between link text and the text box */
  position: relative;
}

.contact-text-box {
  color: #ffffff !important; /* Change this to your desired text color */
  background-color: #7289da; /* Example Discord-like background color */
  padding: 10px 20px;
  text-align: center;
  border-radius: 5px;
  cursor: pointer; /* Change the cursor to indicate it's clickable */
  user-select: none; /* Prevent accidental text selection */
}


/* Remove underline when hovering over the link */
.contact-button a {
  text-decoration: none; /* Ensures no underline on hover */
  color: inherit; /* Inherit the color from the parent (button) */
}

/* Button text */
.contact-button-text {
  z-index: 1;
}

/* Text box next to each button */
.contact-text-box {
  padding: 8px 12px;
  border-radius: 4px;
  background-color: #242424; /* Grey background */
  color: #2c3e50; /* Darker grey text */
  font-size: 14px;
  position: relative;
  z-index: 0;
}

/* Hover effect for the entire button */
.contact-button:hover {
  transform: scale(1.1); /* Slightly scale up on hover */
  border-color: #2c3e50; /* Darker border on hover */
}

/* Specific button colors */
.contact-button.email {
  background: #ffc800; /* Yellow for email */
}

.contact-button.email:hover {
  background: #c99e02; /* Darker yellow on hover */
}

.contact-button.discord {
  background: #5226ff; /* Blue for discord */
}

.contact-button.discord:hover {
  background: #411fcf; /* Darker blue on hover */
}

.contact-button.itchio {
  background: #ff1f5a; /* Red for itch.io */
}

.contact-button.itchio:hover {
  background: #bd113f; /* Darker red on hover */
}


.kofi-button {
  display: inline-block;
  transition: transform 0.3s ease; /* Smooth zoom effect */
}

.kofi-button:hover svg {
  transform: scale(1.1); /* Slight zoom effect */
  transition: transform 0.3s ease; /* Smooth scaling animation */
}

/* Banner Image */
.banner-img {
  width: 100%;
  border-radius: 6px;
  border: 1px solid #30363d;
}

/* Horizontal Line */
hr {
  border: 1px solid #30363d;
}

/* Responsive Adjustments */
@media (max-width: 600px) {
  .stats img {
    max-width: 100%;
  }

  .artwork img,
  .animations img {
    max-width: 100%;
  }
}
