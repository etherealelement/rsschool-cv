
[rsschool-cv](https://github.com/etherealelement)
===========================================================

Vitaly Safonov
===============
### Trainee Frontend Developer

* * *

### Contact information:

*   **Phone:** +7(906)-431-95-35 
*   **E-mail:** vitalik.safonov@list.ru
*   **Telegram:** @etherealelement 
*   [Codewars](https://www.codewars.com/users/ethereal%20element)  
*   [GitHub](https://github.com/etherealelement)

* * *

### Briefly About Myself:

Having a veterinary education and more than 3 years of experience in this field, at the beginning of 2022 I thought about discovering some new direction. Since I have always liked working with a computer since childhood, the choice fell on programming, and soon on Frontend development

I had to combine the work of a veterinarian with the study of web technologies at full load for 8-9 hours at work, I always found time to study and did not think for a minute about changing the chosen direction.

I am studying and really love frontend development, because this activity brings me pleasure and endless opportunities for development and career growth, in the future I want to become a professional developer - to be a master of my craft and open my own Frontend development school.
* * *

### Skills and Proficiency:

*   HTML5, CSS3
*   JavaScript Basics 
*   JavaScript Advanced
*   React
*   TypeScript
*   Git, GitHub
*   VS Code


* * *

### Code example:

**Find the unique number from CODEWARS:** _Write a function called findUnique which returns the only unique number from an array.All numbers in the unsorted array are present twice, except the one you have to find. The numbers are always valid integer values between 1 and 2147483647, so no need for type and error checking. The array contains at least one number and may contain millions of numbers. So make sure your solution is optimized for speed_

    function findUnique(arr) {
  let uniq = new Set();
  let uniqSum = 0;
  let numSum = 0;


  for (let index = 0; index < arr.length; index++) {
    const current = arr[index];

    if(!uniq.has(current)) {
      uniq.add(current);
      uniqSum += current;
    }
    numSum += current;
  }

  return uniqSum * 2 - numSum;
}
    

* * *
