# Yevhenii Khovaiev

## Contact information:
**Phone number:** +38 095 659 06 32  
**E-mail:** ekhovaev@gmail.com  
**Telegram:** @khovaiev  
**GitHub:** [eugenekhovaiev](https://github.com/eugenekhovaiev)

## Briefly About Myself:
I am a student from Kyiv. I like to learn new things, especially when it's interesting to me. I'm learning quickly and patiently. I have a big positive experience working with cliens and other team members, so my soft skills are at pretty high level. I am not afraid of hard and responsible work. I am sure, that after to this course, I`ll become an excellent web developer.

## Skills:
* HTML5, CSS3 (SASS/SCSS, BEM)
* JavaScript Basics
* C
* Git, Github
* VS Code
* Figma, Avocode

## Code example:

Function to ask user about `n` recently watched movies and it's rating, then pushes answers to `movieDB`. Uses endless `while()` cycle to control correct input format.

```javascript
function rememberMyFilm(movieDB, n) {
  let oneOfLastWatchedMovies,
      movieRating;

  for (let i = 0; i < n; i++) {
    while (true) {
      oneOfLastWatchedMovies = prompt('Один из последних просмотренных фильмов?', '').trim();
      if (oneOfLastWatchedMovies && oneOfLastWatchedMovies.length <= 50) {
        console.log('done name');
        break;
      } else {
        console.log('name error');
      }
    } 
    while (true) {
      movieRating = prompt('На сколько оцените его?', '').trim();
      if (movieRating) {
        console.log('done rating');
        break;
      } else {
        console.log('rating error');
      }
    }
    movieDB.movies[oneOfLastWatchedMovies] = movieRating;
  }
}
```

## Experience:
**Couple simple landings**:
* [Pulse](https://eugenekhovaiev.github.io/Pulse/src)
* [Uber](https://eugenekhovaiev.github.io/Uber/src)

## Education:
#### Univercity:
* NTUU ''Igor Sikorsky Kyiv Polytechnic Institute''

#### Courses:
* Udemy: HTML / CSS
* Udemy: JavaScript
* CS50x 2022

## English level:
**B2** Upper intermediate