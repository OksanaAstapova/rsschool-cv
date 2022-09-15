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