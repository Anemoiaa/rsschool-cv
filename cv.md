# Gerogiy Petrov 
## Junior Software Engineer
\
**Contact Information:**

Phone: +000-000-000  
Email: georgiypetroff@gmail.com  
GitHub: [@anemoiaa](https://github.com/anemoiaa/)  
LinkedIn: [Link](https://www.linkedin.com/in/georgiy-petrov-74669b238/)  

**Skills:**
+ HTML5, CSS3, 
+ JavaScript, React, React Router
+ TailwindCSS, Styled Components
+ PHP, Drupal
+ Docker
+ Git  

**Code Example:**

```javascript
// Flatten an array

const x = [
    1, 2, [3, [4, 5 , [6, 7], 8]], [9]
];

function flatten(arr) {
    const result = []; 
    arr.forEach(el => {
        if(Array.isArray(el)) {
            result.push(...flatten(el));
        } else {
            result.push(el);
        }
    })
    return result;
}

console.log(flatten(x));
// outupu: [1, 2, 3, 4, 5, 6, 7, 8, 9]

```
***



**Languages:**   
+ English - B2   
+ Russian - Native  
+ Georgian - Native
