# Astemir Maremkulov

## Contacts 

- **Email:** amaremkulov96@gmail.com
- **Telegram:** [@drooopy](https://t.me/drooopy) 
- **Github** [@metanol596](https://github.com/metanol596)

## About me

My goal is to review the fundamental topics I have previously studied and learn something new. I have some experience working within a startup where we work on various small projects. In my free time, I try to reinforce my old knowledge by watching video courses, educational videos, reading articles, and learning something new

## Skills

- ReactJS, NextJS
- JavaScript, TypeScript
- Redux
- HTML, CSS, Sass, Less
- Webpack, Gulp
- Git
- Figma, Photoshop

## Code examples

```

const checkStringLength = (checkedString, maxStringLength) => {
  const stringLength = checkedString.textLength;
  const WARNING_MESSAGE = `Длина сообщения - ${stringLength} / ${maxStringLength}`;
  
  if (stringLength > maxStringLength) {
    checkedString.setCustomValidity(WARNING_MESSAGE);
  } else {
    checkedString.setCustomValidity('');
  }
  
  checkedString.reportValidity();
};

```

***Codewars kata:*** 
**Count characters in your string**

_Count all the occurring characters in a string. If you have a string like **aba**, then the result should be `{'a': 2, 'b': 1}`. If the string is empty, then the result should be empty object literal, `{}`_

```

function count (string) {  
  let cache = {};
  
  if (string) {
    const res = string.split('').reduce((cache, curr) => {
      
      if (!cache[curr]) { 
        cache[curr] = 0;
      }
       
      cache[curr]++;
      
      return cache;
    }, cache);
    
    return res;
  }
  
  return {};
}

```

## Experience 

- JGate - small startup. I have been involved in projects such as:

_Projects:_
- Project for a private clinic,
- NFT Marketplace

## Education

### Courses

* [HTML Academy](https://htmlacademy.ru/) - HTML, CSS, JS, React, TypeScript, Redux (Basics)
* Udemy
  + React (Juriy Bura)
  + NextJS, TypeScript (Anton Larichev)

## English level

I have not checked my English language proficiency. I have had almost no language practice, both spoken and written. I can understand simple phrases when listening and read simple texts. The more complex the text, the more often I need to look up words in the dictionary. I don't think I have at least an intermediate level, but I am definitely not a beginner
