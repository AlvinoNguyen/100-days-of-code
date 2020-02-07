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