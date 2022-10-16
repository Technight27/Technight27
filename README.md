# Profile

<!--
[![LINKEDIN](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)]([https://www.linkedin.com/in/ayan-maiti-5b4332233/](https://www.linkedin.com/in/sayan-mondal-96852a1b6/))
[![GMAIL](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sayancoder27@gmail.com)
[![DISCORD](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/channels/@me)-->
[![forthebadge](https://forthebadge.com/images/badges/made-with-markdown.svg)](https://forthebadge.com) &nbsp;
[![forthebadge](https://forthebadge.com/images/badges/powered-by-overtime.svg)](https://forthebadge.com) &nbsp;
const express = require('express')
const app = express()

const PLACES = 7;

// no db - so global var to keep track of count
let counter = 0

function getCountImage(count) {
   ...
}

// get the image
app.get('/count.svg', (req, res) => {
  counter++;
  
  // This helps with GitHub's image cache 
  //   see more: https://rushter.com/counter.svg
  res.set({
  'content-type': 'image/svg+xml',
  'cache-control': 'max-age=0, no-cache, no-store, must-revalidate'
  })
  
  // Send the generated SVG as the result
  res.send(getCountImage(counter));
})

const listener = app.listen(process.env.PORT, () => {
  console.log('Your app is listening on port ' + listener.address().port)
})

[![GITHUB FOLLOWERS](https://img.shields.io/github/followers/moonman369?style=social)](https://github.com/Technight27")&nbsp; &nbsp;
![GitHub User's stars](https://img.shields.io/github/stars/Technight27?style=social) &nbsp; &nbsp;
![PROFILE VISITS](https://visitor-badge.glitch.me/badge?page_id=Technight27.Technight27)<br><br>



### Hi there 👋


- 🔭 I’m currently working on cpp
- 🌱 I’m currently learning python, DSA, AI, ML
- 👯 I’m looking to collaborate on projects
- 🤔 I’m looking for help with data structures and algorithms
- 💬 Ask me about anything,am happy to help
- 📫 How to reach me: sayancoder27@gmail.com
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

