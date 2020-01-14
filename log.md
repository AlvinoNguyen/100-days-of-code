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

**Today's Progress**: Finished the product landing page. Solved Problems 1 and 2 on Project Euler using Javascript.

**Thoughts**: Now that the product landing page is finished, I can reflect on things that I can improve on when it comes to CSS. Most importantly, I need to get into the habit of planning out the layout of my page before rushing into projects. I believe my code will be formatted way better if I have a general idea of what I want my page to look like beforehand. This includes properties such as coloring, size, and responsiveness. Also, I need to get used to using CSS variables more often to make my code more readable and writeable.

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

The next project I'm supposed to work on is my personal portfolio, but I'm going to hold off on working on that for now. I think the best thing for me to do now is to practice my Javascript and hopefully move onto React!

**Link to work**: [Technical Documentation Page](https://github.com/AlvinoNguyen/Technical-Documentation-Page)

### Day 12: January 13, Monday

**Today's Progress**: Set up a [Create React App](https://github.com/facebook/create-react-app) page for the random quote machine as specified by the user stories on freeCodeCamp. Set up the skeleton code for styling for the page.

**Thoughts**: Unfortunately, yesterday was my first missed day of the 100 Days of Code challenge. However, it's time to pick myself back up and continue to build my developer skills. Today, I decided to start up the Front End Libraries Projects, which turned out to be a great idea! The random quote machine is a good starting project for React, because the components are very simple. However, to finish the project, I'm gonna have to learn about stateful components and fetch in Javascript. Hopefully this won't be too big of a learning curve!

**Link to work**: [Random Quote Machine](https://github.com/AlvinoNguyen/Random-Quote-Machine)