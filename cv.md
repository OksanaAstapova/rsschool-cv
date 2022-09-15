# **OKSANA ASTAPOVA**


---------------------------------------------------------------

### CONTACTS:

* **Phone:** +375 29 742-59-21 
* **e-mail:** astapova.frontend@gmail.com
* **Skype:** live:pitjay_1
* **LinkedIn:** [oksana-astapova](https://www.linkedin.com/in/oksana-astapova/)
* **Telegram:** [@Pitjay](@Pitjay)
* **Discord:** Oksana Astapova#0262

----------------------------------------------------------------

### ABOUT:

> So, let me tell you about myself: I was Middle school English teacher at the age of 34. But as you know in Belarus we have dictatorship by Lukashenko and his those close. After the events of August 2020 and cruelty against the people of our poor country, we decided to leave here. My husband has been working in Lithuania almost a year and waiting for my relocation.

> Then, as becoming a web designer has always been my dream, I completed Michigan State University courses (HTML5, CSS, JavaScript, Responsive design) and Hong Kong Technical University courses (jQuery, Bootstrap, Git, Less/Sass, Angular), Coursera courses (WordPress). Also, my English is good enough, so the result of the EF Standard English Test is C1 (Advanced level). 

>  As for my personal qualities, I am creative, active and easy to learn, communicative and a good team player.

---------------------------------------------------------------------

### SKILLS:

+ **Languages:** JavaScript, Typescript
+ **Technologies:** JavaScript, HTML5, SASS, CSS, Bootstrap, Webpack, REST API, NPM, Angular, WordPress
+ **Tools:** Chrome Dev Tools, Figma, Canva, PerfectPixels, Photoshop, CodePen
+ **Source Control:** Git
+ **OS:** Windows
+ **IDE:** Visual Studio Code, Sublime Text 3
+ **Accomplishments:** 
 1. Applications implemented using Single-Page Application approach
 2. Implemented projects using Vanilla JavaScript and clean CSS

---------------------------------------------------------------------

### CODE EXAMPLE:

```typescript
async function removeDifficult(i: number){

  const wordCloseButton = document.getElementById(`difficult-remove ${i}`) as HTMLElement;
  const word: Word = wordCloseButton.parentElement?.parentElement;
  const wordsIds: string = getWordIdFromStorage('word-id');

  const ids = wordsIds.split(',');
  ids.forEach(id => {
    if(id === word?.id){
      let i = ids.indexOf(id);
      ids.splice(i, 1);
    }
  })
  localStorage.setItem("word-id", JSON.stringify(ids));
  
  word?.remove();

  const userId = getfromStorage('id');

  const content = await getUserWords(userId);
  content.forEach(el => {
    if(el.wordId === word?.id){
      const id = el.wordId;
      deleteUserWord(userId, id)
    }
  })
}
```
-------------------------------------------------------------------------------------

### EXPERIENCE:

***RsLang***
Single-Page Application for learning English words with usage of Kanban desk for managing tasks by plan
[RsLang](https://rslang-oksana-astapova.netlify.app/)

*Accomplishments:*
+ Organized a work in a team of three as a team-lead
+ Implement the textbook with a MongoDB database, mini-games and statistics page for tracking individual progress.
+ Router implementation for the data flow
+ Implementation backend deployment on heroku
+ Implementation of user authentication using REST API and Bearer Token. Managed different user states depending on its authorization status


***Race***
Simple game in browser based on creation of different cars and run racing.
[Race](https://drive.google.com/file/d/1mF4uoemSDMG5BAIpVrfRFxQn5-TGPIXl/view?usp=sharing)

*Accomplishments:*
+ Implementation of Single Page Application divided to different logical modules allows to maintain the codebase in the easiest way
+ Implementation of communication with server via REST API allows to store all the data remotely
+ Collection of all the data about races allows users to see it’s history and leaderboard statistics of his cars.

***Online store***
Online store that allow users look for products, sort it, apply different filters, like prices, colors, sizes, search by name add products to cart. 
[Online Store](https://prismatic-squirrel-848bd4.netlify.app)

*Accomplishments:*
+ Usage of Local storage API allows to save current information about cart even when user left the page
+ Manipulation with data allows users to filter products by different parameters and sort it.
+ Dynamic update of cart items allow to simplify user experience without duplicate items in cart, just with updating it’s quantity.

***Virtual Keyboard***
Virtual keyboard that allows user to input text into the text fields using hardware keyboard together with keyboard UI rendered on web page.
[Virtual Keyboard](https://oksanaastapova.github.io/virtual--keyboard/)

*Accomplishments:*
+ Responsive design, implemented in this project, highlighting UI in use after pressing hardware keyboard buttons allows user have greater user experience and usability
+ Connection with hardware keyboard gives users variety of input between hardware keyboard and manually clicking buttons on web
+ Written in Vanilla JavaScript which keeps code clean, simple and small as much as it’s possible

***Shelter for pets***
Website that allow people to help different pets, check detailed information about each, open shelters location in Google Maps
[Shelter for pets](https://rolling-scopes-school.github.io/oksanaastapova-JSFE2022Q1/shelter/pages/main/)

*Accomplishments:*
+ Pagination and adaptive design gives user best experience looking throw the list of pets displaying the exact amount of information that fits particular screen
+ Implementation of actions gives the possibility to see exact shelter locations in different cities in google maps.
+ Implementation of burger menu gives users perfect navigation experience on a small screens

 
***UAB MK BALTIC***
Corporate website that provides information about services and products company provides
[MkBaltic](https://oksanaastapova.github.io/MK_Baltic/)

*Accomplishments:*
+ Implementation of different rediractions based on selection allow select prefered connection type for users
+ Slider written in Vanilla JavaScript which keeps code clean, simple and small as much as it’s possible
+ Adaptive design gives user best experience in displaying the exact amount of information that fits particular screen
+ Implementation of burger menu gives users perfect navigation experience on a small screens


***CSS mem-slider***
Interactive website with funny images written without usage of JavaScript
[mem-slider](https://oksanaastapova.github.io/cssMemSlider/cssMemSlider/)

*Accomplishments:*
+ All the project written using only CSS without additional languages
+ Adaptive design gives user best experience in displaying the exact amount of information that fits particular screen
+ Different animations provides comfortable user experience

--------------------------------------------------------------------

### EDUCATION:

***University of Michigan***
[Specialization: Basics of Web Development & Coding](https://www.coursera.org/account/accomplishments/specialization/UU47PJ4GHJ7W)

***The Hong Kong University of Science and Technology***
[Courses technologies: Angular & Bootstrap](https://www.coursera.org/account/accomplishments/verify/RY27KLA62XPB)

https://www.coursera.org/account/accomplishments/verify/WQKS8XDBPWQ8

***Coursera Course Certificates***
[Courses technologies: Wordpress & Typescript](https://www.coursera.org/account/accomplishments/verify/3AG6CQ9XKXG2)

https://www.coursera.org/account/accomplishments/verify/GE8F5G79P4WK

***Bachelor of Arts 2010***
Mogilev State University 
Department of foreign languages
Graduation project: The Versailles Treaty and its practical realization

***EF Standard English Test (EF SET)***
[Result: C1 Advanced level](https://www.efset.org/cert/9vdhttps://www.efset.org/cert/9vdYrEYrE)