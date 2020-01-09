# 100 Days Of Code - Log

### Day 1: January 1, Wednesday

**Today's Progress**: Forked and customized Alex Kallaway's 100 Days of Code repo to my liking.

**Thoughts**: Markdown is cool! I should continue getting familiar with Markdown so that I can write better README.md and other .md files on Github.

**Link to work**: [Forked 100 Days of Code Repository](https://github.com/AlvinoNguyen/100-days-of-code)

### Day 2: January 2, Thursday

**Today's Progress**: Started building a tribute page according to the user stories specified by freeCodeCamp.

**Thoughts**: I am rusty on pure HTML and CSS, so it will take me a few projects in order to get used to working with these two web technologies again. Luckily, there are many pure HTML and CSS projects on freeCodeCamp!

**Link to work**: [Tribute Page](https://github.com/AlvinoNguyen/Tribute-Page)

### Day 3: January 3, Friday

**Today's Progress**: Finished the tribute page, and created the skeleton code for the survey form according to the user stories specified by freeCodeCamp.

**Thoughts**: The most challenging part of HTML and CSS is that you don't receive any explicit errors. This makes it hard to detect nuances in your code, especially in CSS. Also, I think I have a gap in my learning when it comes to HTML forms! I'll have to find tutorials in order to catch up and continue working tomorrow.

**Links to work**:
1. [Tribute Page](https://github.com/AlvinoNguyen/Tribute-Page)
2. [Survey Form](https://github.com/AlvinoNguyen/Survey-Form)

### Day 4: January 4, Saturday

**Today's Progress**: Added new types of input to the survey form, including a dropdown, radio buttons, checkboxes, and a text area. Also added basic styling to the form.

**Thoughts**: There was not as much progress as I wanted today. I got a bit lazy during the middle of the day, and therefore didn't get to coding until the evening. However, I did get a lot of coding done because I also coded for my work today. However, according to the [rules](rules.md), if I code at work, that time won't count towards the challenge.

**Link to work**: [Survey Form](https://github.com/AlvinoNguyen/Survey-Form)

### Day 5: January 5, Sunday

**Today's Progress**: Finished styling the survey form.

**Thoughts**: CSS is easy to learn, yet hard to master. I will need a lot more practice if I want to be able to call myself 'proficient' in CSS. However, I'm happy with the way I styled the survey form, but I know that there are more elegant ways to achieve the same styling that I coded up.

**Link to work**: [Survey Form](https://github.com/AlvinoNguyen/Survey-Form)

### Day 6: January 6, Monday

**Today's Progress**: Created the skeleton code for the product landing page according to the HTML user stories specified by freeCodeCamp. Also started styling the page.

**Thoughts**: This project has a larger CSS portion because you have to create a more complex layout using Flexbox. This project also requires that you use media queries to make the page more responsive, which is something I need to learn how to do better. I also want to get into the habit of creating my layouts *mobile-first*, and then adding media queries later for desktop layouts. I think this project will take significantly longer than the last two, so I may start up another project before I finish this one.

**Link to work**: [Product Landing Page](https://github.com/AlvinoNguyen/Product-Landing-Page)

### Day 7: January 7, Tuesday

**Today's Progress**: Continued styling the product landing page. In particular, I added responsive styles to the mini-form, the features section, and the footer.

**Thoughts**: I'm noticing that I have to repeat myself a lot when coding CSS today. To alleviate this, I should get used to working with the more complex features of CSS, like variables and functions. I should also look into Sass and maybe even Bootstrap, but those are for another time. I think I'll have this project done by the end of the week, and I'm still debating on what I should work on after, since I'm getting bored on pure HTML/CSS.

**Link to work**: [Product Landing Page](https://github.com/AlvinoNguyen/Product-Landing-Page)

### Day 8: January 8, Wednesday

**Today's Progress**: Finished the product landing page. Solved Problems 1 and 2 on Project Euler using Javascript.

**Thoughts**:
Now that the product landing page is finished, I can reflect on things that I can improve on when it comes to CSS. Most importantly, I need to get into the habit of planning out the layout of my page before rushing into projects. I believe my code will be formatted way better if I have a general idea of what I want my page to look like beforehand. This includes properties such as coloring, size, and responsiveness. Also, I need to get used to using CSS variables more often to make my code more readable and writeable.

Secondly, from now on, I want to incorporate a bit of rigorous problem solving into my 100 Days of Code challenge. My plan is to supplement my normal project coding with coding puzzles from sites such as [Project Euler](https://projecteuler.net/), [Leetcode](https://leetcode.com/), and possibly even [Codeforces](http://codeforces.com/). In addition to Javascript, I want to sharpen my C++ skills for the sake of coding interviews. However, I won't make it a mandatory rule because of how much problem solving I already do in my classes.

**Links to work**:
1. [Product Landing Page](https://github.com/AlvinoNguyen/Product-Landing-Page)
2. [Multiples of 3 and 5](https://projecteuler.net/problem=1)
    <details>
    <summary>Solution</summary>
    <br>

    ```js
    let sum = 0;

    for(let i = 1; i < 1000; i++) {
        if(i % 3 == 0)
        sum += i;
        if(i % 5 == 0)
        sum += i;
        if(i % 15 == 0)
        sum -= i;
    }

    console.log(sum);
    ```
    </details>
3. [Even Fibonacci numbers](https://projecteuler.net/problem=2)
    <details>
    <summary>Solution</summary>
    <br>

    ```js
    sum = 2;

    let f_n_1 = 2;
    let f_n_2 = 1;

    let f_n = f_n_2 + f_n_1;

    while(f_n < 4000000) {
        if(f_n % 2 == 0) sum += f_n;
        f_n_2 = f_n_1;
        f_n_1 = f_n;
        f_n = f_n_2 + f_n_1;
    }

    console.log(sum)
    ```
    </details>