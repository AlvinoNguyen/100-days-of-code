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

**Thoughts**: I'm noticing that I have to repeat myself a lot when coding CSS today. To alleviate this, I should get used to working with the more complex features of CSS, like variables and functions. I should also look into Sass and maybe even Bootstrap, but those are for another time. I think I'll have this project done by the end of the week, and I'm still debating on what I should work on after, since I'm getting bored of pure HTML/CSS.

**Link to work**: [Product Landing Page](https://github.com/AlvinoNguyen/Product-Landing-Page)

### Day 8: January 8, Wednesday

**Today's Progress**: Finished the product landing page. Solved Problems 1 and 2 on Project Euler using JavaScript.

**Thoughts**: Now that the product landing page is finished, I can reflect on things that I can improve on when it comes to CSS. Most importantly, I need to get into the habit of planning out the layout of my page before rushing into projects. I believe my code will be formatted way better if I have a general idea of what I want my page to look like beforehand. This includes properties such as coloring, size, and responsiveness. Also, I need to get used to using CSS variables more often to make my code more readable and writeable.

Secondly, from now on, I want to incorporate a bit of rigorous problem solving into my 100 Days of Code challenge. My plan is to supplement my normal project coding with coding puzzles from sites such as [Project Euler](https://projecteuler.net/), [Leetcode](https://leetcode.com/), and possibly even [Codeforces](http://codeforces.com/). In addition to JavaScript, I want to sharpen my C++ skills for the sake of coding interviews. However, I won't make it a mandatory rule because of how much problem solving I already do in my classes.

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
    let sum = 2;

    let f_n_1 = 2;
    let f_n_2 = 1;
    let f_n = f_n_2 + f_n_1;

    while(f_n < 4000000) {
        if(f_n % 2 == 0) sum += f_n;
        f_n_2 = f_n_1;
        f_n_1 = f_n;
        f_n = f_n_2 + f_n_1;
    }

    console.log(sum);
    ```
    </details>

### Day 9: January 9, Thursday

**Today's Progress**: Created the skeleton code for the technical documentation page according to the user stories specified by freeCodeCamp. Also solved three problems on Leetcode in C++.

**Thoughts**: I'm starting to notice how much faster I can get going when it comes to HTML/CSS projects compared to when I first started, so I'm making progress! For this project, I'm taking the opportunity of the subject to learn about [AWK](https://en.wikipedia.org/wiki/AWK), a domain-specific language designed for text processing and typically used as a data extraction and reporting tool. Hopefully the learning time doesn't cut too much into coding time!

On the other hand, I'm glad to be coding in C++ again. It's not like I have to relearn the basics, but I'm constantly looking up the methods of STL data structures. Hopefully as I solve more problems, I'll drill the most common methods back into my brain.

**Links to work**:
1. [Technical Documentation Page](https://github.com/AlvinoNguyen/Technical-Documentation-Page)
2. [Reverse String](https://leetcode.com/problems/reverse-string/)
    <details>
    <summary>Solution</summary>
    <br>
    
    ```cpp
    void reverseString(vector<char>& s) {
        // Initialize pointers
        int start = 0;
        int end = s.size() - 1;

        while(start < end) {
            // Swap values at pointers
            char temp = s[start];
            s[start] = s[end];
            s[end] = temp;
            
            // Move pointers
            start++;
            end--;
        }
    }
    ```
    </details>
3. [Valid Anagram](https://leetcode.com/problems/valid-anagram/)
    <details>
    <summary>Solution</summary>
    <br>

    ```cpp
    bool isAnagram(string s, string t) {
        unordered_map<char, int> map;

        // Adding characters of s to map
        for(int i = 0; i < s.size(); i++) {
            if(map.find(s[i]) != map.end())
                map[s[i]]++;
            else
                map[s[i]] = 1;
        }

        // Removing characters of t from map
        for(int i = 0; i < t.size(); i++) {
            if(map.find(t[i]) != map.end())
                map[t[i]]--;
            else
                return false;
        }

        // Checking if keys in map have a value of 0
        for(auto i: map) {
            if(i.second != 0)
                return false;
        }

        return true;
    }
    ```
    </details>
4. [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/)
    <details>
    <summary>Solution</summary>
    <br>

    ```cpp
    int firstUniqChar(string s) {
        unordered_map<char, int> map;
        
        // Add unique characters to map
        for(int i = 0; i < s.size(); i++) {
            if(map.find(s[i]) == map.end())
                map[s[i]] = i;
            else
                map[s[i]] = -1;
        }
        
        // Find first unique character in map
        int min = INT_MAX;
        for(auto i: map) {
            if(i.second != -1 && i.second < min)
                min = i.second;
        }
        
        // Return -1 if index is not found,
        // otherwise, return the minimum index
        return min == INT_MAX ? -1 : min;
    }
    ```
    </details>

### Day 10: January 10, Friday

**Today's Progress**: Completed the styling for the technical documentation page, as well as added more content. Solved three problems on Leetcode in C++.

**Thoughts**: My CSS is a lot more readable and consise than the last project! This is thanks to both the simple layout of my page, as well as my use of CSS variables. Despite all of this, I don't necessarily think my styling looks good, but I suppose that comes with practice. My goal is to be able to style modern-looking web pages with pure CSS.

**Links to work**:
1. [Technical Documentation Page](https://github.com/AlvinoNguyen/Technical-Documentation-Page)
2. [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
    <details>
    <summary>Solution</summary>
    <br>

    ```cpp
    int maxProfit(vector<int>& prices) {
        // Represents the current minimum
        // on a given day
        int min = INT_MAX;
        // Represents the best possible
        // transaction on a given day
        int max = 0;

        for(int i = 0; i < prices.size(); i++) {
            // Update min if necessary
            if(prices[i] < min)
                min = prices[i];

            // Update max if necessary
            if(prices[i] - min > max)
                max = prices[i] - min;
        }

        return max;
    }
    ```
    </details>
3. [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)
    <details>
    <summary>Solution</summary>
    <br>

    ```cpp
    bool containsDuplicate(vector<int>& nums) {
        unordered_set<int> set;
        
        for(int i = 0; i < nums.size(); i++) {
            // Insert int into set if it's unique
            if(set.find(nums[i]) == set.end())
                set.insert(nums[i]);
            else
                return true;
        }
        
        return false;
    }
    ```
    </details>
4. [Move Zeroes](https://leetcode.com/problems/move-zeroes/)
    <details>
    <summary>Solution</summary>
    <br>

    ```cpp
    void moveZeroes(vector<int>& nums) {
        // Keeps track of index to place value
        int index = 0;

        // Place all non-zero values in front
        for(int i = 0; i < nums.size(); i++) {
            if(nums[i] != 0)
                nums[index++] = nums[i];
        }

        // All non-zero values are placed in front,
        // so all values are zero in the back
        for(int i = index; i < nums.size(); i++)
            nums[i] = 0;
    }
    ```
    </details>

### Day 11: January 11, Saturday

**Today's Progress**: Added more HTML content to the technical documentation page. Also made the content more semantic.

**Thoughts**: Today was a bit unproductive when it comes to web development, but it's okay, because I'm done with the technical documentation page! Working on this project also helped me learn the basics of AWK a little better, and I'm hoping that I'll be able to apply this knowledge in the future! I'm proud of how I did on this project because how much more elegant my code looks on both the HTML and CSS side.

The next project I'm supposed to work on is my personal portfolio, but I'm going to hold off on working on that for now. I think the best thing for me to do now is to practice my JavaScript and hopefully move onto React!

**Link to work**: [Technical Documentation Page](https://github.com/AlvinoNguyen/Technical-Documentation-Page)

### Day 12: January 13, Monday

**Today's Progress**: Set up a [Create React App](https://github.com/facebook/create-react-app) page for the random quote machine as specified by the user stories on freeCodeCamp. Set up the skeleton code for styling for the page.

**Thoughts**: Unfortunately, yesterday was my first missed day of the 100 Days of Code challenge. However, it's time to pick myself back up and continue to build my developer skills. Today, I decided to start up the Front End Libraries Projects, which turned out to be a great idea! The random quote machine is a good starting project for React, because the components are very simple. However, to finish the project, I'm gonna have to learn about stateful components and fetch in JavaScript. Hopefully this won't be too big of a learning curve!

**Link to work**: [Random Quote Machine](https://github.com/AlvinoNguyen/Random-Quote-Machine)

### Day 13: January 14, Tuesday

**Today's Progress**: Added the skeleton code for props and state for the appropriate componenets in the random quote machine.

**Thoughts**: Today, I spent a long time getting used to writing React componenets, so I did a lot of experimenting. In particular, I learned about the props and state, and I'm currently learning about how to handle events in React. After I learn that, I'll need to learn about JavaScript fetch in order to finish this project. This is my favorite project so far, so I don't mind all the learning!

**Link to work**: [Random Quote Machine](https://github.com/AlvinoNguyen/Random-Quote-Machine)

### Day 14: January 15, Wednesday

**Today's Progress**: Added color as a state property for the random quote machine. Also added random color functionality to the app.

**Thoughts**: Now that I'm starting to learn new things while simultaneously working on projects at the same time, my progress is gonna be slower than it has been in the past 14 days. However, doing these projects also means that I'll learn about web development more effectively! That being said, I'm not sure if I should move on to another project and come back to the random quote machine when I know more about fetch, or if I should continue working and eventually finish this project. That's a decision for another day!

**Link to work**: [Random Quote Machine](https://github.com/AlvinoNguyen/Random-Quote-Machine)

### Day 15: January 16, Thursday

**Today's Progress**: Added a feature that fetches random quotes online.

**Thoughts**: It only took a bit of experimenting, but I was able to use JavaScript fetch to get random quotes online in JSON format, which is then integrated into my app. I also attempted to link the media buttons to their respective pages so that the quotes are already typed up when they go to the website. The problem I faced was that I couldn't put functions inside of my data/*.js files. There is probably a better way to do what I wanted to do, so I will keep learning and following tutorials. Tomorrow, I should be wrapping up this project.

**Link to work**: [Random Quote Machine](https://github.com/AlvinoNguyen/Random-Quote-Machine)

### Day 16: January 17, Friday

**Today's Progress**: Finished the random quote machine. Completed two problems on freeCodeCamp's JavaScript Algorithms and Data Structures Projects.

**Thoughts**: I don't know why, but I didn't run into the problem of putting functions inside of my data/*.js files. From there, making the media buttons work was pretty easy, and now there's not much more I need to do in terms of functionality. I could try to add animations to the app, but that's something I want to save for later.

There's not much to say about the problems I solved since they were straightforward. There are three more project problems on freeCodeCamp, and they are a lot more difficult than the ones I solved today. If I have time, maybe I'll finish them over the weekend.

**Links to work**:
1. [Random Quote Machine](https://github.com/AlvinoNguyen/Random-Quote-Machine)
2. [Palindrome Checker](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/javascript-algorithms-and-data-structures-projects/palindrome-checker)
    <details>
    <summary>Solution</summary>
    <br>

    ```js
    function palindrome(str) {
        let l = 0;
        let r = str.length - 1;
        while(l < r) {
            const regex = /[A-Z0-9]/i;
            while(!regex.test(str.charAt(l))) l++;
            while(!regex.test(str.charAt(r))) r--;

            if(l >= r) return true;
            const lChar = str.charAt(l);
            const rChar = str.charAt(r);
            if(lChar.toLowerCase() != rChar.toLowerCase()) return false;
            l++; r--;
        }
        return true;
    }
    ```
    </details>
3. [Caesars Cipher](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/javascript-algorithms-and-data-structures-projects/caesars-cipher)
    <details>
    <summary>Solution</summary>
    <br>

    ```js 
    function rot13(str) {
        let result = '';

        for(let i = 0; i < str.length; i++) {
            if(!/[A-Za-z]/.test(str.charAt(i))) result += str.charAt(i);
            else result += String.fromCharCode(str.charCodeAt(i)%26+65);
        }
        
        return result;
    }
    ```
    </details>

### Day 17: January 18, Saturday

**Today's Progress**: Started the mini-project of recreating Google's front page.

**Thoughts**: I woke up sick today, and I didn't feel like I had the capacity to learn and code React in the same day. However, that doesn't mean that I can't practice what I've already learnt! Therefore, I decided to start this mini-project, which was an idea that I've had for a long time, but never got around to doing. I like this project because it forces me to carefully consider my CSS choices, which is something I could always improve on. This project shouldn't take long, and ideally, I'll finish it tomorrow.

**Link to work**: [Google Look Alike](https://github.com/AlvinoNguyen/Google-Look-Alike)

### Day 18: January 19, Sunday

**Today's Progress**: Finished the mini-project of recreating Google's front page.

**Thoughts**: This was a fun mini-project to pick up! I even learned some new things about CSS along the way, such as outlines and box-shadows. Surprisingly, Google's front page isn't responsive, so I didn't have any practice in responsive web design. Next time I decide to do a mini-project again, I'll try to incorporate it.

I also got to thinking about where I should go in terms of projects. I believe that I jumped into React a little too quickly, and that the best thing for me to do is to take a step back and learn about fundamental JavaScript topics, such as JSON, the DOM, the Fetch API, and ES6 features. I don't think it will take too long, and I also have the perfect project to start learning more about JavaScript!

**Link to work**: [Google Look Alike](https://github.com/AlvinoNguyen/Google-Look-Alike)

### Day 19: January 20, Monday

**Today's Progress**: Started the recreation of my random quote machine using pure Javscript.

**Thoughts**: I decided to compare pure JavaScript and React when it comes to basic DOM manipulation. Since I've only completed one React project, I thought it would be a good idea to take that project and redo it in pure JavaScript. It was super easy to recreate, since I had basically coded all the HTML and CSS beforehand in the React project. Manipulating the DOM in pure JavaScript was also very straightforward, so I currently have almost all the same functionality as the React project. It shouldn't take long to code in everything else.

**Link to work**: [Random Quote Machine 2](https://github.com/AlvinoNguyen/Random-Quote-Machine-2)

### Day 20: January 21, Tuesday

**Today's Progress**: Finished the recreation of the random quote machine. Started the mini-project of recreating Netflix's front page.

**Thoughts**: The random quote machine didn't take long to finish. All I had to do was set the href attribute of the Twitter button every time I fetched a quote. I want to do at least one more pure JavaScript project so that I get a little more practice with the DOM, JSON, and the Fetch API.

Meanwhile, things are getting a little busy at school, but it's nice to come here and code for myself every day! Today, I mostly spent my hour recreating Netflix's front page because I saw how simple Netflix's UI is. It's a little more challenging than Google's front page because I have to take into account responsiveness and layout more carefully.

**Links to work**:
1. [Random Quote Machine 2](https://github.com/AlvinoNguyen/Random-Quote-Machine-2)
2. [Netflix Look Alike](https://github.com/AlvinoNguyen/Netflix-Look-Alike)

### Day 21: January 22, Wednesday

**Today's Progress**: Finished recreating Netflix's front page.

**Thoughts**: There's not much to say about today. I have a lot of work due in the upcoming days, so most of my focus has gone to that. However, I did manage to squeeze an hour of web development practice in throughout the day. This mini-project was interesting because I used a lot of new CSS properties. For example, I learned a little bit about absolute positioning, as well as image responsiveness! Tomorrow, I still start a new JavaScript project.

**Link to work**: [Netflix Look Alike](https://github.com/AlvinoNguyen/Netflix-Look-Alike)

### Day 22: January 23, Thursday

**Today's Progress**: Added CSS transitions to the JavaScript random quote machine. Wrote the skeleton code for the freeCodeCamp local weather project.

**Thoughts**: Today I was watching an HTML, CSS, and JavaScript tutorial for a Rock, Paper, Scissors project when I stumbled upon CSS transitions. Transitions are simple way to add animations to CSS elements, and I've essentially fallen in love with them. I decided to try them out in my random quote machine, and it made the UX feel way more smooth. It isn't perfect though. From what I gathered, there's no easy way to adjust responsive width and height with transitions, so the height of my quote box still has a choppy transition.

Another thing I stumbled upon today was freeCodeCamp's take home projects. It's a great list of 20 ideas for web development projects, and I decided to ditch my To Do List project idea for this one: An app that checks the local weather. I'm doing this project a little bit differently, because I'm doing the DOM manipulation stuff with HTML and JavaScript before doing the styling with CSS. Now that I'm creating dynamic web projects, I think a better workflow for solo projects is to create a fully functioning app before adding the styling. That way, the functionality of the program isn't dictated by the styling.

**Links to work**:
1. [Random Quote Machine 2](https://github.com/AlvinoNguyen/Random-Quote-Machine-2)
2. [Local Weather](https://github.com/AlvinoNguyen/Local-Weather)

### Day 23: January 24, Friday

**Today's Progress**: Refactored JavaScript in the local weather project. Added HTML geolocation functionality.

**Thoughts**: I think this is all the JavaScript I'll need to do for this project. I used a lot of new concepts and techniques today, such as DOM caching, Date objecets, asynchronous JavaScript, callback functions, and HTML geolocations. It turns out there's a lot about JavaScript that I still don't know! However, as long as I look into asynchronous JavaScript, I think I should be fine to move back to React. Tomorrow, we're styling this bad boy!

**Link to work**: [Local Weather](https://github.com/AlvinoNguyen/Local-Weather)

### Day 24: January 25, Saturday

**Today's Progress**: Added styling to the introduction of the local weather project.

**Thoughts**: I didn't get as much styling as I wanted to today. It's okay; there are always gonna be slow days like this. However, I am applying new CSS concepts. Mainly, I'm trying to avoid using ID selectors to avoid having my styling too connected to the semantics. Also, text ad box shadows are kinda cool!

**Link to work**: [Local Weather](https://github.com/AlvinoNguyen/Local-Weather)

### Day 25: January 26, Sunday

**Today's Progress**: Added additional information section to the local weather project, including styles and functionality.

**Thoughts**: Today was pretty interesting, because I coded in HTML, CSS, and JavaScript simultaneously. The code in HTML and JavaScript was straightforward stuff, but the CSS was interesting because I used CSS Grid for the first time. Grid is a different lay to page layouts, and I think it would be helpful to practice it more. When I'm doing with this project, hopefully my next project will lend itself naturally to a Grid layout instead of a Flexbox one.

**Link to work**: [Local Weather](https://github.com/AlvinoNguyen/Local-Weather)

### Day 26: January 27, Monday

**Today's Progress**: Added sunrise and sunset times to the additional info section of the local weather project. Added styles themes that change depending on the time of day.

**Thoughts**: This was another slow day, but it was a good JavaScript-learning hour. Working on Date objects and asynchronous Javascript is a bit confusing, but I think I'm getting the hang of it. I also decided add the day/night styles, which turned out to look really good! It's gonna take a while to get styles for each type of weather though.

**Link to work**: [Local Weather](https://github.com/AlvinoNguyen/Local-Weather)

### Day 27: January 28, Tuesday

**Today's Progress**: Added fahrenheit and celcius toggle buttons.

**Thoughts**: All the implementations I've done in the past few days feel very repetitive, which I think is a good thing, because it means I'm ready to move back to React. However, I do want to finish up this project to the best of my ability, and I'm one step closer to doing that with the addition of fahrenheit and celcius buttons. Although a small feature, it helped me practice CSS transitions and encouraged me to refactor my Javascript! Tomorrow, I'll try to put the final touches to this project, but there's no guarantee, because I have an insanely busy day!

**Link to work**: [Local Weather](https://github.com/AlvinoNguyen/Local-Weather)

### Day 28: January 29, Wednesday

**Today's Progress**: Added a basic Express backend to the pure JS random quote machine.

**Thoughts**: I'm surprised that I haven't done any backend coding this year until today. I think that adding backend code to my projects so that they can be run on the local host is a good idea because it will help me get familiar with Node and Express. Also, it opens up the opportunity for me to learn about databases. Unfortunately, this was all I had time to do today, but it was an hour of coding!

**Link to work**: [Random Quote Machine 2](https://github.com/AlvinoNguyen/Random-Quote-Machine-2)

### Day 29: January 31, Friday

**Today's Progress**: Implemented a fix for the 'Shuzenji' bug in the local weather app. Also added 'loading' values to temperature elements and an interval to update the weather.

**Thoughts**: Wow, it's been a hectic couple of days! Unfortunately, I didn't have the time to code last night as I was cramming for a midterm. I guess I should take this as an indication to try to improve my time management skills!

Anyway, I finished up my local weather app! This project took a lot longer than I expected, but I also used a lot more JavaScript concepts than I expected too. Some of the notable concepts from this project were DOM manipulation, Date objects, higher-order functions, fetch, promises, and event listeners. That's a lot of concepts, and I think this means I'm finally ready to move on to coding up React projects!

**Link to work**: [Local Weather](https://github.com/AlvinoNguyen/Local-Weather)

### Day 30: February 1, Saturday

**Today's Progress**: Started the timestamp microservice project following the user stories specified by freeCodeCamp. Added skeleton code and implemented backend.

**Thoughts**: I don't know what it is about backend recently, but I've really wanted to start a backend-focused project. It turns out that the first backend (full stack) project on freeCodeCamp was really easy to implement, so I finished the backend in an hour. If all goes well, I'll be done with this quick project tomorrow, and I can move on to more complex backend projects.

**Link to work**: [Timestamp Microservice](https://github.com/AlvinoNguyen/Timestamp-Microservice)

### Day 31: February 2, Sunday

**Today's Progress**: Added HTML content and CSS styles to the timestamp microservice project. Fixed a bug in the backend code.

**Thoughts**: I feel like I'm hitting a plateau when it comes to learning new things for HTML and CSS. I'll learn a few new things with every project I do, but my end product looks about the same. I should try to find a resource to help me improve my CSS skills, but I think it's more important for me to develop my all-around web development skills. That being said, I finished the timestamp microservice, and I'll be starting a new project tomorrow!

**Link to work**: [Timestamp Microservice](https://github.com/AlvinoNguyen/Timestamp-Microservice)

### Day 32: February 3, Monday

**Today's Progress**: Created a request header parser microservice following the user story specified by freeCodeCamp.

**Thoughts**: This will probably be the quickest I ever finish a project during these 100 days. This project is basically a copy of the last project (all the way down to recycled HTML structure and CSS styles!), except instead of giving back a timestamp, I gave back information about the client's device. To be honest, this project was a lot simpler than the last one, except I did a little bit NPM and Express spelunking to figure out the right functions to call.

**Link to work**: [Request Header Parser Microservice](https://github.com/AlvinoNguyen/Request-Header-Parser-Microservice)

### Day 33: February 4, Tuesday

**Today's Progress**: Started the Java Battleship project.

**Thoughts**: Today, I decided to take a trip down memory lane and do a little bit of coding in Java. It was the first programming language I ever learned, so it feels pretty cool to be coding in it again. I decided to create a text-based Battleship game which can be played inside the terminal. So far, I have a lot of the boilerplate code down, and I should be getting to the hard stuff tomorrow!

**Link to work**: [Java Battleship](https://github.com/AlvinoNguyen/Java-Battleship)

### Day 34: February 5, Wednesday

**Today's Progress**: Edited the Grid class for the Java Battleship game. Implemented a prototype of the Player class.

**Thoughts**: To be honest, today's hour of code felt more like busy work instead of learning new things. However, if I continue working on this game, the next thing I'll need to implement is the Battleship class, which will be a lot more interesting (and a lot more difficult!). I'm excited!

**Link to work**: [Java Battleship](https://github.com/AlvinoNguyen/Java-Battleship)

### Day 35: February 6, Thursday

**Today's Progress**: Started and added skeleton code for the Battleship class.

**Thoughts**: There's a lot more nuances when it comes to making a text-based game, and it's especially bad whenever you're trying to get input from the user. Every time I ask for the user to give input, I need to check if the input is valid. This isn't difficult, but it's extremely tedious, and this will seriously slow down my progress. Maybe it would be a good idea to start another project while continuing to work on this one...

**Link to work**: [Java Battleship](https://github.com/AlvinoNguyen/Java-Battleship)

### Day 36: February 7, Friday

**Today's Progress**: Added functionality to the Battleship class so that the player can add ships to his/her grid.

**Thoughts**: I've been super busy lately, which is a shame, because that means I can only code on my own for an hour a day. I'm not sure how much progress I'm making with this game, but I can confidently say that I'll be done by the end of next week. This is taking a while for something that was supposed to me a mini-project!

**Link to work**: [Java Battleship](https://github.com/AlvinoNguyen/Java-Battleship)

### Day 37: February 8, Saturday

**Today's Progress**: Moved all I/O formatting methods into the Print class. Added computer random ship setting and guessing functionality.

**Thoughts**: The Battleship class is getting so big that I've been trying to move some methods to a different class. However, the Battleship class is still pretty big. I don't think it'll get much bigger than this though, because I'm pretty close to finishing. All I have to do after today is to alternate between the player's and computer's guesses, and then determine a winner at the end of the game.

**Link to work**: [Java Battleship](https://github.com/AlvinoNguyen/Java-Battleship)

### Day 38: February 9, Sunday

**Today's Progress**: Modularized user input functions in the Battleship class. Added player guessing and score functionality.

**Thoughts**: I've gotten about 95% of the functionalty for the Battleship game down. After that, I'll feel okay moving to a new project. However, there's probably a few bugs that I haven't caught in this program, so I should spend some time looking for those.

**Link to work**: [Java Battleship](https://github.com/AlvinoNguyen/Java-Battleship)

### Day 39: February 10, Monday

**Today's Progress**: Added simple check to determine winner of the game. Added functionality to check when a ship has been sunk.

**Thoughts**: It's time to say farewell to this Java Battleship game! I thought this project would take at most a day, but this ended up being a week-long project, which might be the longest I've ever spend on one ever since I started the 100 days. It took longer than expected, but at least I never gave up on this project! Maybe one day, I come back to Java to code up another minigame, but for now, I need to focus on web development again!

**Link to work**: [Java Battleship](https://github.com/AlvinoNguyen/Java-Battleship)

### Day 40: February 11, Tuesday

**Today's Progress**: Added skeleton code to the freeCodeCamp URL Shortener Microservice Project.

**Thoughts**: It feels good to be back coding in HTML/CSS/JS again! I'm a bit rusty on some of the content since I essentially haven't done any web development in about a week, but it doesn't feel like I forgot anything super important, so that's good! Also, if I'm gonna fully finish this project, I'm gonna have to implement a database, meaning I'll have to learn MongoDB. That'll be quite the challenge, because I've never touched it before!

**Link to work**: [URL Shortener Microservice](https://github.com/AlvinoNguyen/URL-Shortener-Microservice)

### Day 41: February 12, Wednesday

**Today's Progress**: Added skeleton functionality and styles to the form of the URL Shortener Microservice Project.

**Thoughts**: Not a lot happened today, but it's kind of a historic moment. Today, I created my first post function in the 100 days! It took quite a lot of learning and experimenting to get everything working, but everything seems to be working now. I still have a bit of backend work and styling to do before I can call this a finished project!

**Link to work**: [URL Shortener Microservice](https://github.com/AlvinoNguyen/URL-Shortener-Microservice)

### Day 42: February 13, Thursday

**Today's Progress**: Added code to save URLs and revisit them later using the shortened URL.

**Thoughts**: Again, today was a lot of experimentation, especially with the Express redirect function. At one point, I accidently created a permanent redirect (since I didn't know what the 301 status code was), and had to clear my data to get rid of it. However, the basic functionality of the form is almost complete! All I have to do now is tinker with the dns.lookup function to allow `http://` and `https://` prefixes.

**Link to work**: [URL Shortener Microservice](https://github.com/AlvinoNguyen/URL-Shortener-Microservice)

### Day 43: February 15, Saturday

**Today's Progress**: Implemented URL validator to the server's POST request.

**Thoughts**: This implementation took a lot longer than expected (which is why I didn't log yesterday)! Initially, I attempeted to validate URLs by using using regular expressions, but there were so many edge cases that I had to deal with that I knew there must have been an easier way to do things. It turns out the WHATWG API can be used to parse URL easily. From there, the implementation wasn't too bad. Now, I think I'm done with the backend logic of this project. Tomorrow, I'll work on the CSS. It's been a while since I've done some serious CSS, so I'm a bit rusty!

**Link to work**: [URL Shortener Microservice](https://github.com/AlvinoNguyen/URL-Shortener-Microservice)

### Day 44: February 16, Sunday

**Today's Progress**: Refactored styles for the URL Shortener Microservice. Finished the HTML and CSS for the freeCodeCamp File Metadata Microservice Project.

**Thoughts**: The CSS didn't take that long to finish for the URL Shortener Microservice. There wasn't much else to do for that project, so I moved on to the next freeCodeCamp backend project. Well, actually I skipped the Exercise Tracker project because it seemed like I'd have to learn MongoDB for me to finish completely. This project shouldn't take that long to do since I've finished all the HTML, CSS, and a lot of the backend today. All I have to do is implement the function for the POST request.

**Links to work**: 
1. [URL Shortener Microservice](https://github.com/AlvinoNguyen/URL-Shortener-Microservice)
2. [File Metadata Microservice](https://github.com/AlvinoNguyen/File-Metadata-Microservice)

### Day 45: February 17, Monday

**Today's Progress**: Explored NPM package possibilities for uploading files. Installed Multer package and implemented Multer disk storage to backend code.

**Thoughts**: There was a lot more exploring than coding today, meaning I'm getting to parts of web development that I haven't learned yet. Unfortunately, this means that from now on, progress will happen much slower than it used to. In this case, it looks like I'll have to learn MongoDB to progress further afterall. On the bright side, this means I'll be learning a lot over the next new months!

**Link to work**: [File Metadata Microservice](https://github.com/AlvinoNguyen/File-Metadata-Microservice)

### Day 46: February 18, Tuesday

**Today's Progress**: Started the freeCodeCamp Wikipedia Viewer project.

**Thoughts**: My return to React wasn't as grand as I expected it to be. I was able to build the skeleton code for the Wikipedia Viewer, but I'm already at a loss for how to continue with the project. I forgot a lot about how React works, and the next few days will be about trying to catch up to where I was when I originally created the Random Quote Machine in React. I don't have much time though, since I'm participating in my first hackathon on Sunday!

**Link to work**: [Wikipedia Viewer](https://github.com/AlvinoNguyen/Wikipedia-Viewer)

### Day 47: February 19, Wednesday

**Today's Progress**: Implemented the toggling functionality for the Toggle component for the Wikipedia Viewer project.

**Thoughts**: I got a lot more done than expected! I thought it would take a while to relearn about props, state, and events, but I was able to get done as much as I expected. However, I'm not at the hard part yet. From here, I need a way to pass information up to the App component, and then build new components for the search list.

**Link to work**: [Wikipedia Viewer](https://github.com/AlvinoNguyen/Wikipedia-Viewer)

### Day 48: February 21, Friday

**Today's Progress**: Added functionality to pass input from Toggle to App componenet.

**Thoughts**: I feel like I could have gotten a lot more done today, but I went through a few different strategies to pass input from the Toggle component to the App component. In the end, I passed an App function that takes input as a parameter as a property of the Toggle component. From here, I have to figure out how to use the Wikipedia Search API, as well as implement the Result (and possibly ResultList) component(s).

**Link to work**: [Wikipedia Viewer](https://github.com/AlvinoNguyen/Wikipedia-Viewer)

### Day 49: February 22, Saturday

**Today's Progress**: Added search results functionality to the Wikipedia Viewer project using the Wikipedia Search API.

**Thoughts**: Using fetch with an API is always fun. Today, I spent some time relearning all about component lists. In the end, I used them in the search functionality. Now, searching anything up on this site lets me view the "top" 10 Wikipedia articles given your input. About all the logic is done for this project, so all I have to do now is style it with CSS. I'm glad I chose to work on this project in React. This time, it feels like a framework is better suited for the job than pure JavaScript!

**Link to work**: [Wikipedia Viewer](https://github.com/AlvinoNguyen/Wikipedia-Viewer)

### Day 50: February 23, Sunday

**Today's Progress**: Participated in UCLA's Hack On The Hill 7. Created a Markdown Previewer.

**Thoughts**: Today was my first hackathon, and it was a lot of fun! I came up with the idea (inspired by freeCodeCamp's Markdown Previewer project) of creating an app that transformed Markdown into a semantic PDF file, and over 12 hours, we ended up creating an entire IDE specifically for Markdown. We built our app with React, but unfortunately I didn't get to work on much React. Instead, I helped design the style and layout of the app using pure CSS. After I finish my Wikipedia Viewer, I'm gonna work on my own version of the Markdown Previewer to help me get better at React.

**Link to work**: [Major Markdown](https://github.com/Firius0408/Hack)

### Day 51: February 24, Monday

**Today's Progress**: Started CSS styling for the Wikipedia Viewer project.

**Thoughts**: I ended up using a lot of new CSS properties today! First off, I'm trying out CSS transitions again, which I still find super awesome. It makes my web pages look a lot more modern. I'm also using pseudo-classes for my anchor tags to keep my styles consistent. I even used a pseudo-element just to make hovering over search results look better! In my next projects, I wanna use pseudo-elements a lot more so that I can unlock their full potential. Lastly, I used filters in order to color my images. All in all, today was a good CSS styling session!

**Link to work**: [Wikipedia Viewer](https://github.com/AlvinoNguyen/Wikipedia-Viewer)

### Day 52: February 25, Tuesday

**Today's Progress**: Finished the CSS styling for the Wikipedia Viewer project.

**Thoughts**: Today was pretty straightforward. I changed the toggle input and button so that its style matched the theme of the app. Unfortunately, I have no idea how to add an opening and closing animation of the toggle button. There is proably a way to do create it using CSS animations, but currently I don't know how they work. Maybe it's something I should look into. A few other things that I added to the CSS were transitions to the result class pseudo-element, as well as a media query so that the app looks better on a desktop. This project is essentially done, so now its time to move on to my own version of the Markdown Previewer!

**Link to work**: [Wikipedia Viewer](https://github.com/AlvinoNguyen/Wikipedia-Viewer)

### Day 53: February 27, Thursday

**Today's Progress**: Started the pure HTML/CSS/JS calculator project specified by the user stories on freeCodeCamp.

**Thoughts**: For some reason, Create React App wasn't rendering my page today, even after I spent a while trying to figure out what I was doing wrong. Then I decided to delay React projects until I figure it out. In the meantime, I started this cool project. I can already tell that this project is better meant for React than pure JavaScript, since the code is already pretty tedious. There was a lot of pasting in the HTML, and a lot of rewriting code for the CSS. To be fair though, the CSS isn't necessary, but it makes the calculator look much nicer.

**Link to work**: [JavaScript Calculator](https://github.com/AlvinoNguyen/JavaScript-Calculator)

### Day 54: February 28, Friday

**Today's Progress**: Added basic styling and scripting to the JavaScript calculator.

**Thoughts**: The styling was a lot more simpler than I expected. Most of the work was done with CSS Grid positioning, and the rest of the styling was a few basic color and font commands. On the other hand, the scripting looks like it will be a little more complex. The part I'm most concerned about is the evaluting the infix expression. If there isn't a JavaScript built-in function to do this for me, then I'll have to implement it on my own. I've already seen the algorithm, but its implementation is a bit technical.

**Link to work**: [JavaScript Calculator](https://github.com/AlvinoNguyen/JavaScript-Calculator)

### Day 55: February 29, Saturday

**Today's Progress**: Implemented integer arithmetic functionality to the Javascript Calculator.

**Thoughts**: As I expected, I didn't have to implement the arithmetic evaluation function, since there exists the eval function! It made implemeting the 'equals' button a lot easier to code up. However, I still used a stack in order to save operators and operands in a convenient way. Tomorrow, I'll wrap up this project by implementing floating-point arithmetic. After that, maybe I'll recreate this project using React as an exercise. Despite its simplicity, this might be one of my favorite projects!

**Link to work**: [JavaScript Calculator](https://github.com/AlvinoNguyen/JavaScript-Calculator)

### Day 56: March 1, Sunday

**Today's Progress**: Implemented floating-point arithmetic functionality to the Javascript Calculator. Initialized the React JavaScript Calculator using Create React App.

**Thoughts**: There wasn't much more work I had to do to finish the first JavaScript Calculator, so today I ended up finishing that project in about half an hour. I spent the rest of the hour initializing another repository (the second JavaScript Calculator) using Create React App. For some reason, things are working now, so I must have deleted something I wasn't supposed to a few days ago. Oh well, at least now I can do more React work!

**Links to work**:
1. [JavaScript Calculator](https://github.com/AlvinoNguyen/JavaScript-Calculator)
2. [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 57: March 2, Monday

**Today's Progress**: Added skeleton components to the React JavaScript Calculator.

**Thoughts**: I spent my hour adding the boilerplate code for each component of the React JavaScript Calculator. It was time-consuming and not necessarily difficult, so nothing interesting really happened today. However, something new I'm trying is splitting up my CSS into multiple files. Each component will have its own CSS file, and the App component collects all those styles together to render them to the page. I think this would be good practice for bigger projects, but for something like a calculator, it will be a bit more work than a single file with all the styles.

**Link to work**: [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 58: March 3, Tuesday

**Today's Progress**: Added basic styling to app and button components of the React JavaScript Calculator.

**Thoughts**: Instead of reusing all the styles from my previous JavaScript calculator, I decided to further practice my CSS skills be copying the styles of the iPhone Calculator app. I still get to reuse some of the same styles from my previous project, but soon I'm gonna reach a point where I'll have to modify some of my components to fit the CSS better. Hopefully this isn't too hard of a task. The point of redoing this project is to gain a better understanding of React, not to keep practicing CSS!

**Link to work**: [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 59: March 4, Wednesday

**Today's Progress**: Finished adding layout styles to the React JavaScript Calculator

**Thoughts**: Finishing the layout for all the components for this project was a bit more difficult than I expected, so I didn't get to any of the React logic today. In order to match the style of the iPhone calculator app, I had to wrap all the conponents inside another container inside the app container so I could adjust the height of the grid. Next, to keep myself from messing up the natural margins of the grid, I created a pseudo element in place of a border, which was also a bit tricky. I also had to slightly change the Operator component so that I could give the components valid ids that CSS would recognize. Other than that, everything went pretty smoothly! Tomorrow, I can start the React logic of this calculator.

**Link to work**: [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 60: March 6, Friday

**Today's Progress**: Started React logic for the Number component in the React JavaScript Calculator

**Thoughts**: The logic for this project is a lot more involved than I expected! Today, I was hoping to get through being able to update the current value after each click to a number button, but it's taking longer than I expected. This is partially because I'm trying to limit the numbers on the display to a maximum of 9 digits, as well as trying to pretty format the value. This means adding commas where necessary. Most of the functions I've coded so far are in the App component, but I should look into trying to move these functions into the Number component if appropriate.

**Link to work**: [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 61: March 7, Saturday

**Today's Progress**: Finished logic for the Number and Decimal components in the React Javascript Calculator.

**Thoughts**: While numbers and decimals were the hardest things to implement in the first JavaScript Calculator, they might be the easiest thing I'll have to implement for this calculator. Due to the nature of how I created the Operator component, it's going to be difficult to find an efficient way to add operators to the stack. It's made even more complex because not all operators use their respective symbol for their value (For example, the divide symbol is the value of the divide component rather than `/`). I wonder how long it will take to finish the rest of this project, since I'm getting a bit tired of calculators.

**Link to work**: [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 62: March 9, Monday

**Today's Progress**: Implemented the Operator and Equals components for the React JavaScript Calculator.

**Thoughts**: My code is starting to look a little bloated and confusing since there is so much going on in the App component. The logic for the Operator and Equals components wasn't too difficult to implement, but they revealed a new problem I didn't think about. I limit the numbers that I can type to nine significant figures, but the result of the calculation can go past this limit, which I don't want. After finishing this bug, and after implementing the +/- and % operation buttons, my React JavaScript Calculator should be good to go!

**Link to work**: [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 63: March 11, Wednesday

**Today's Progress**: Implemented negation and percentage operator functionalities, as well as fixed floating-point bugs in the React JavaScript Calculator.

**Thoughts**: Limiting the result of the calculation to nine significant digits is actually a lot more difficult than I expected. Today, I was running around confused as to why big numbers were displaying as big integers on the app, while displaying as exponentials on the console. It's because the console has a unique algorithm for printing out floating-point numbers. However, I don't know what this algorithm is, or how to implement it on the display component. Eventually, I moved on and implemented the rest of the operators, as well as fixed a few crucial bugs.

**Link to work**: [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 64: March 13, Friday

**Today's Progress**: Fixed the display formatting of small floating-point numbers in the React JavaScript Calculator.

**Thoughts**: I feel like I'm almost done! In today's attempt to fix the formatting for big numbers, I ended up finding a bug relating to small numbers. First, I formatted the display value to show only nine significant digits. I had to take into account the small epsilon error of floating-point numbers, and for some reason, `Number.EPSILON` was only recognized when I typed it in the browser. Therefore, I coded its exact value in my rounding function.

From there, I was almost done except for a few cases. Sometimes, the number would take the form of X,e-Y, where X was a single digit. What I wanted to do was remove the comma before the e. I was able to do this using the regular expression `/,[e-]/g` and the string replace function. I felt pretty proud of myself for fixing that bug today!

**Link to work**: [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 65: March 15, Sunday

**Today's Progress**: Fixed the display formatting of large integers in the React JavaScript Calculator.

**Thoughts**: I've finally wrapped up the React JavaScript Calculator, which means I can finally move on to a new project! It turns out that the function that I needed to compress large integers was the `Number.toExponential`. If I had figured out how to properly use this function a few days ago, would that have saved me days of writing and tracing through spaghetti code? I don't know, but the calculator is done and working properly now :)

I have a few ideas for what my next project should be. My first idea was to make a sorting algorithm visualizer. It would be a good test of my React and CSS skills and would serve a relatively practical purpose. My other idea was to make chessboard game. I've been playing Chess recently, and I want to code up a game that would help me recognize the position of certain squares on the board faster. I might end up doing both during the 100 days, but which should I start first...?

**Link to work**: [JavaScript Calculator 2](https://github.com/AlvinoNguyen/JavaScript-Calculator-2)

### Day 66: March 17, Tuesday

**Today's Progress**: Initialized Chess Vision React App and added basic styles to the Grid component.

**Thoughts**: Unfortunately, when I checked my Github profile today, I realized that I had 0 contributions for two days in a row for the first time this year! However, that doesn't mean I've broken my streak for this 100 Days of Code challenge, even though I have been regularly skipping every other day. Trust me, after Finals Week ends, I'll have a lot more time and motivation for web development!

Today's progress was pretty straightforward. I started the Chess Vision React App that I talked about last entry using React Create App, and I formatted the `src` directory to my liking. Then, I added basic structure and styling to the Grid component. I have to say: the biggest takeway I'll get from these 100 days is sharpened CSS skills, which I have been honing since the very beginning. It's getting a lot easier to style my projects, which is a good thing, because later on, I don't want to spend too much of my projects on CSS!

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 67: March 19, Thursday

**Today's Progress**: Added the basic functionality to the Chess Vision React App.

**Thoughts**: Surprisingly, the basic functionality wasn't too difficult to implement even though it was a lot more involved than I expected. First, I learned that it's illegal to set the state of a component in its `render` or `componentDidMount` function, because this would lead to an infinite rendering loop. Besides this, I didn't *learn* a lot, but I did use a lot concepts that I don't have a lot of practice with. For example, I used events and classic DOM manipulation to implement the `handleSquareClick` function in order to temporarily change the styles of certain elements. Since I'm basically done with the basic functionality, all I have to do is add extra features to the app!

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 68: March 21, Saturday

**Today's Progress**: Added a prototype of the Sidebar component for the Chess Vision React App.

**Thoughts**: The first thing I want to add to the Chess Vision App is a good user interface, or at least one that matches the one on [Chess.com](https://www.chess.com/). This involves a form where you can select the options for the Chess Vision game. This includes the orientation of the board with respect to the color, as well as whether you want to show coordinate helpers or not. Both of these (and the form itself) seem a bit tricky to implement, so I'll be working on this for the next few days!

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 69: March 23, Monday

**Today's Progress**: Implemented primitive timing functionality to the Chess Vision React App. 

**Thoughts**: It turns out that counting down from 3, 2, to 1 is a lot more difficult than it looks. When I try to set multiple timeouts, all the code runs at the same time because of asynchronous JavaScript. In other words, this means there is a pause at 3, and then it instantly goes down to 1, which is what I don't want. With how I implemented it, I am making each timeout longer than the last to compensate for asynchronous JavaScript, but there must be a better way of doing this...

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 70: March 25, Wednesday

**Today's Progress**: Added basic game functionality to the Chess Vision React App.

**Thoughts**: The better way of doing things is not much better, but it makes much more sense: Callbacks. Unfortunately, this means my code has to be super nested. If I knew a little bit more about promises, then maybe I could make my code look more elegant, but my code suffices right now. It was enough to let me code up the basic game functionality of the app.ewe Currently, my game works, but you can't see statistics, and you can't configure the game. That's what I'll be working on for the next few days.

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 71: March 27, Friday

**Today's Progress**: Implemented the functionality for the 'Show Coordinates' checkbox for the Chess Vision React App.

**Thoughts**: Today, I coded up one of the core features of the app, but it wasn't super complicated. Most of the code I wrote involved passing down props to child componenets, setting state, and handling events. Essentially, it was all basic React. The next part might also involve only basic React, but it will be logically difficult. I have to update the chessboard squares depending on the value of the 'Color' input value. I'm excited though. This app might be my favorite project that I'm going to make in the 100 days!

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 72: March 29, Sunday

**Today's Progress**: Implemented the functionality for the 'Color' selection for the Chess Vision React App.

**Thoughts**: Today's code was essentially the same as the last entry with a little bit more logic involved. Surprisingly, it wasn't hard logic either, since I only had to add and change a few lines of code to make the color selection work. I guess I can thank my decent implementation of each component and the relationship between components. Essentially, I'm done with the core implementation of the app. All I need to do now is to add game statistics. That shouldn't be too hard, since I'm getting used to working with props and state.

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 73: March 30, Monday

**Today's Progress**: Started the Stats class for the Chess Vision React App.

**Thoughts**: I was a bit distracted today, so I didn't get a lot done. However, the Stats class has been started, and I'm expecting to finish it within a day or two. After that, I might be finished with this project!

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 74: March 31, Tuesday

**Today's Progress**: Added grid color, current coordinate, success count, and timer to the Stats component in the Chess Vision React App.

**Thoughts**: Again, there wasn't too much difficulty today. There's one more feature that I plan on adding tomorrow, but it shouldn't be too difficult, since it will involve much of the same concepts that I've coded up in the past few days. One interesting thing I learned today was that `setInterval` returns an id. I always thought `setInterval` was a function that didn't return anything. This id is used for whenever you want to clear the interval using `clearInterval`.

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 75: April 1, Wednesday

**Today's Progress**: Added coordinate list to the Stats component in the Chess Vision React App.

**Thoughts**: I'm glad to finally announce that I am finished with all the functionality of this app! However, there are a few things that I want to change before I move on to the next project. First off, I want to replace the empty boxes with appropriate images that match the theme of the app. Then, I have to edit the CSS to make the app responsive! My guess is that I won't have to touch any JavaScript to do this, but I might also prettify the JavaScript code as a final touch.

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 76: April 3, Friday

**Today's Progress**: Added responsiveness to the Grid component of the Chess Vision React App.

**Thoughts**: I feel like today was a big lesson on mobile-first development and responsive design. It turns out that I can't do much when it comes to responsiveness because my styles were implemented to work on only my monitor. When it comes to CSS, generalizing is much more difficult, and at this point would involve a complete rework of the CSS for each component. However, I think there are small changes I can make to the CSS to allow it to work on most desktops. It will be slow, but it'll be worth it in my opinion.

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 77: April 5, Sunday

**Today's Progress**: Added vector images to the appropriate components of the Chess Vision React App.

**Thoughts**: After some thinking, I have decided against trying to rework the styles and structure of the app in order to make it more responsive. I'll take this project as a lesson learned about keeping responsive design in the back of my head whenever I build something. That being said, I am proud to say that I am finished with the Chess Vision React App! This is my first big web game I've created, and I'm glad to see how it turned out. One day, I'll attempt to make this project more responsive, but that's for another day. It's time to move on with the next project!

**Link to work**: [Chess Vision](https://github.com/AlvinoNguyen/Chess-Vision)

### Day 78: April 7, Tuesday

**Today's Progress**: Created the skeleton components for the freeCodeCamp Pomodoro Clock App.

**Thoughts**: I had two projects in mind for after the Chess Vision App: A sorting algorithm visualizer, or my personal portfolio. Considering the fact that I will be looking for a job in the near future, I should prioritize the portfolio, but the sorting algorithm visualizer seems much cooler! I decided to defer the decision and work on a freeCodeCamp project. The Pomodoro Clock App is on a much smaller scale than the Chess Vision App, meaning this shouldn't take too long. I am essentially done with the HTML parts, and can move on to coding the logic tomorrow.

**Link to work**: [Pomodoro Clock](https://github.com/AlvinoNguyen/Pomodoro-Clock)

### Day 79: April 8, Wednesday

**Today's Progress**: Added functionality to all the components of the Pomodoro Clock App.

**Thoughts**: Coding up the logic for this small app was pretty easy since the Chess Vision App gave me a ton of practice with `state` and `props`. That's not even mentioning the once-confusing (but now straightforward) `setInterval()` and `clearInterval()` functions. Tomorrow, I plan on adding styles to the page. This time, I'm coming up with my own styles, so hopefully the app won't look *too* ugly by the time I'm done.

**Link to work**: [Pomodoro Clock](https://github.com/AlvinoNguyen/Pomodoro-Clock)

### Day 80: April 9, Thursday

**Today's Progress**: Added the main styles to the Pomodoro Clock App.

**Thoughts**: I decided to go with a minimalist appoach to the styling of this app, and it turned out pretty well! I first started off styling the only the layout of the app, and this time I didn't forget to make it responsive. Well, to be honest, I only used one media query since the app was small. Then I ended up creating another `.css` extension file that focused on the colors of the app. This means I can change the theme of my app without having to dig though the CSS layout code!

**Link to work**: [Pomodoro Clock](https://github.com/AlvinoNguyen/Pomodoro-Clock)

### Day 81: April 11, Saturday

**Today's Progress**: Added selection styles to the Pomodoro Clock App. Started the Sorting Visualizer App.

**Thoughts**: It turns out that there wasn't much else I could do with the Pomodoro Clock, so it was time to move on to the next project. I decided that my next (and probably last, at least for the 100 days) project will be the Sorting Visualizer App that I talked about a few weeks ago. I have the general idea in my head, and I tried coding up a bit of it in a top-down approach. Instead of starting with the App component, I tried coding the child components first, but I make a mistake. I forgot that state can't be passed up to parent components! I should know better considering how long I've coded in React, but at least I know now.

**Links to work**:
1. [Pomodoro Clock](https://github.com/AlvinoNguyen/Pomodoro-Clock)
2. [Visual Sort](https://github.com/AlvinoNguyen/Visual-Sort)

### Day 82: April 13, Monday

**Today's Progress**: Refactored code for the Sorting Visualizer App.

**Thoughts**: I did a lot of tinkering with my code today. It looks like this is gonna be another project that's heavy on asynchronous concepts. I had to rework a lot of the code I did yesterday, but I was able to recycle a good amount of it too!

**Link to work**: [Visual Sort](https://github.com/AlvinoNguyen/Visual-Sort)

### Day 83: April 15, Wednesday

**Today's Progress**: Implemented selection sort, insertion sort, and bubble sort for the Sorting Visualizer App.

**Thoughts**: I did a little bit of work after I wrote the last entry, and ended up getting the shuffle function working with a smooth animation. The animating was the hardest part because it required timeouts to happen synchronously, and the way I was able to force that was though a function that resolved a promise after some time. However, after figuring that out, the logic was pretty easy, since I've seen implemented all of these algorithms before. I also want to implement mergesort and quicksort, but they're a bit tricky. 

**Link to work**: [Visual Sort](https://github.com/AlvinoNguyen/Visual-Sort)

### Day 84: April 17, Friday

**Today's Progress**: Implemented mergesort for the Sorting Visualizer App.

**Thoughts**: It was a long day, so I went into coding super tired. However, I was able to implement all of mergesort! I decided not to go with the in-place merging algorithm for simplicity, and I think that was the right choice. For relatively small numbers, the lag caused by memory isn't too big of a deal. Next time, I'll try to implement quicksort. I've never implemented quicksort before, so this should be fun!

**Link to work**: [Visual Sort](https://github.com/AlvinoNguyen/Visual-Sort)

### Day 85: April 19, Sunday

**Today's Progress**: Implemented quicksort for the Sorting Visualizer App.

**Thoughts**: Quicksort is actually not that bad to implement! In fact, after I wrap my head around why the partition algorithm, works, I'd see quicksort just as intuatively as mergesort! For now though, this is all the sorting algorithms I'll implement. Next time, I'll finally start working on the user interface. However, I wanna leave myself room to implement two more algorithms: Shell sort and heap sort.

**Link to work**: [Visual Sort](https://github.com/AlvinoNguyen/Visual-Sort)

### Day 86: April 21, Tuesday

**Today's Progress**: Added basic layout and styles to the Sorting Visualizer App.

**Thoughts**: It feel good to be styling again! This time, I've decided to go for a simple 8-bit theme, which I think works really well with the bars. Once I style the buttons the way I want them to look, I think the entire app will look very clean! However, I do need to be more careful with the layout of my page. I might get to a point in styling where I realize that my layour isn't responsive, and I'd have to do it all over again. Hopefully it doesn't get to that point!

**Link to work**: [Visual Sort](https://github.com/AlvinoNguyen/Visual-Sort)

### Day 87: April 23, Thursday

**Today's Progress**: Improved layout and added basic styles to the Sorting Visualizer App.

**Thoughts**: Today's progress wasn't very interesting. I added some styles to the buttons, and I reworked the layout of the app. I decided to use CSS Grid for a lot of things instead of Flexbox, which helped a bit with the responsive design. However, I'm still having a few problems when the width goes under 800 pixels. Next time, I'll try to find a fix for that, and if I have time, I'll try to implement heapsort too.

**Link to work**: [Visual Sort](https://github.com/AlvinoNguyen/Visual-Sort)

### Day 88: April 25, Saturday

**Today's Progress**: Implemented heapsort for the Sorting Visualizer App.

**Thoughts**: I didn't feel like doing CSS today, so I decided to go ahead and just implement heapsort. Again, this was my first time implementing it, but this algorithm felt a lot more simple than mergesort and quicksort. That's probably because heapsort doesn't use any recursion, and arrays can be used to represent heaps quite well. With the implementation of heapsort, I'm done with all the sorting algorithms I planned on including in this app. All I have to do is finish making the layout responsive and I'm done!

**Link to work**: [Visual Sort](https://github.com/AlvinoNguyen/Visual-Sort)

### Day 89: April 27, Monday

**Today's Progress**: Added final touches to the Sorting Visualizer App.

**Thoughts**: There wasn't much left to do for the Sorting Visualizer App, so all I did today was add final touches to the project. First, I added a crude locking mechanisms to each of the buttons. Now, every time a button is clicked, a flag is set which makes sure no other button can be pressed until the algorithm is done running. I also added a few styles and fixed the layout of the page when viewed on a mobile device. I thought this project would take longer than this, and now I need to think of something to work on for the last 11 days of this challenge...

**Link to work**: [Visual Sort](https://github.com/AlvinoNguyen/Visual-Sort)

### Day 90: April 29, Wednesday

**Today's Progress**: Started my personal portfolio webpage.

**Thoughts**: It's about time that I made myself a website! I was feeling a bit uncreative today, so I decided to go with a super minimal look and just focus on the layout. I have a navigation bar, a header, and a few extra sections so far. If I'm still gonna go for minimal, that might be all I need! 

**Link to work**: [Personal Portfolio](https://github.com/AlvinoNguyen/Personal-Portfolio)

### Day 91: May 1, Friday

**Today's Progress**: Added a viewport event handler to my personal portfolio webpage.

**Thoughts**: I forgot to mention last time; I'm going back to basics and using only pure HTML, CSS, and JavaScript for my portfolio. I don't imagine that my website will have much interactivity, so it's probably best if I keep things as simple as possible. That being said, I'm pretty proud of the feature I implemented today! I coded an event handler to check to element visibility, meaning I can run code in response to something popping up on the page. My plan is to use it to make the styling on my website more dynamic.

**Link to work**: [Personal Portfolio](https://github.com/AlvinoNguyen/Personal-Portfolio)