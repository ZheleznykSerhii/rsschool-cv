### Zheleznyk Serhii

**Phone: +38 (093) 853 95 67**
**Email: sergeyzheleznik@gmail.com**

# Summary of Qualifications

html, css, js, react-redux

# Skills

• I am easy-going person with experience of work at head offices of big Ukrainian banks.
• In addition, I used to study abroad, so it is easy to me to collaborate with people from different countries.

# Experience / IT related educational practice

• From November to January I improved my knowledge of banking business and from February I learn front-end technologies.
• August 2019 - October 2020 - I used to work in Kyiv at Raiffeisen bank in credit risks department.
• 2018 - 2019 - work at Idea bank( financial risks department). Did tasks at Excel, made reports for internal usage of my department and for the board
• 2016 - Nestle Business service. My job was to prepare outsource account reports for UK market.

# Languages

English – intermediate.
Polish – intermediate

# Education

• 2009 - 2015 Lviv banking institute, banking business

• 2014 - 2016 Krakow economy university, banking business

# Additional education (courses, trainings)

I finished 23 hours course about basic js https://coursehunter.net/course/sovremennyy-javascript-s-samogo-nachala
At the moment study at this React course
https://www.youtube.com/watch?v=auAtFC5nfTs&ab_channel=IT-KAMASUTRA

Also I finished HTML and CSS courses.

An example of code

````// Please enter the words, letters, digits, or sentences at variable "userInput"
let userInput = 'aaAAaaabracadabra qweЕЕЕtv$$bnnnn'

//Please enter the number of symbols for calculating (1-3)
let b = 3

userInput = userInput.toLowerCase()
userInput = userInput.replace(/[^A-Za-zА-Яа-яЁё\d]/g, "")

let mass = []

if(b===1){
  for(let i = 0; i < userInput.length; i++){
    mass.push(userInput[i])}


  }

if(b===2){
for(let i = 0; i < userInput.length-1; i++){
  mass.push(userInput[i]+userInput[b-1+i])}

}

if(b===3){
  for(let i = 0; i < userInput.length-2; i++){
    mass.push(userInput[i]+userInput[b-2+i]+userInput[b-1+i])}

  }

    counts = {},
    freq = [];
for (var i in mass) {
    counts[mass[i]] = (counts[mass[i]] || 0) + 1;
}
Object.keys(counts).sort(function(a, b) {
  return counts[b] - counts[a]
}).forEach(function(el) {
  freq.push([el, counts[el]]);
});



freq = freq.slice(0, 10)

/* Якщо результат має подаватися не у вигляді звичайного об'єкту (хоча після маніпуляцій тайпоф freq залишиться об'єкт), то можна зняти коментарій зі строк 48, 54 і 50, або 52 одночасно закоментувавши строку 56. Тоді подання відповіді буде також близьким до шаблону.*/
//for(let i = 0; i < freq.length; i++){

//console.log(`["${freq[0]}] ["${freq[1]}] ["${freq[2]}] ["${freq[3]}] ["${freq[4]}] ["${freq[5]}] ["${freq[6]}] ["${freq[7]}] ["${freq[8]}] ["${freq[9]}]`);
//У строці 50 не використовую [i], бо через [i] в консолі результат виводиться в стовпчик, а не в рядок як на прикладі. Проте можна і через [і], як у строці 52.
//console.log(`["${freq[i]}]`);

//}

console.log(freq) ```
````
