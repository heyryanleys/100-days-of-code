# 100 Days Of Code - Log

### Day 0: January 1, 2018
<table>
  <tr>
    <td width="50%" valign="center"><img src="/images/day1_1.png" /></td>
    <td width="50%" valign="center"><img src="/images/day1_2.png" /></td>
  </tr>
</table>


**Today's Progress**: Worked on building a minesweeper app as part of the Codecademy course I'm taking

**Thoughts:** This took me longer than the other stages of making the minesweeper game so far. I was working on it yesterday and ended up deleting the entire file this afternoon and starting over.  Going through the steps was much easier this time, but I'm still frustrated that until I read the steps I can't think of what they would be.

**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Minesweeper game
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/unit-1/minesweeper/src/minesweeper.js)  

### Day 1: January 2, 2018  

**Today's Progress**: Took notes about control flows, built a magic 8 ball app and an app that tells racers their start time based on their age the time they registered.

**Thoughts:** Thought this was much easier than yesterday-- I've used if else statements a lot in the past so the class part of today was pretty easy, although I didn't know about switch statements which seem very useful.

**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Day 13
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/tree/master/unit-1/Day_13_Control%20Flow)  

### Day 2: January 3, 2018  

**Today's Progress**: Worked on the minesweeper game in my Codecademy course. Today I compared the bomb board and the player board to show when the tile contained a bomb, and if it didn't it would show the number of how many bombs were surrounding it.

**Thoughts:** This drove me nuts at first because I was having a very hard time understanding this method:  

```
neighborOffsets.forEach(offset => {
  const neighborRowIndex = rowIndex + offset[0];
  const neighborColumnIndex = columnIndex + offset[1];
  if (neighborRowIndex >= 0 && neighborRowIndex < numberOfRows && neighborColumnIndex >= 0 && neighborColumnIndex < numberOfColumns){
    if (bombBoard[neighborRowIndex][neighborColumnIndex] === 'B'){
      numberOfBombs++;
    };
  };
});
```  

It still is slightly confusing to me-- I'm going to repeat today's lesson tomorrow to make sure I can understand this before moving forward.

**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Minesweeper game
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/unit-1/minesweeper/src/minesweeper.js)  

### Day 3: January 4, 2018  

**Today's Progress**: Did yesterdays lesson from Codecademy again today

**Thoughts:** Had an easier time than yesterday but still having a tough time with this one, I have to move on to the next lesson tomorrow to not get behind, but I want to come visit this in a few days and see if the next lessons help me understand this one better.


**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Minesweeper game
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/unit-1/minesweeper/src/minesweeper.js)  

### Day 4: January 5, 2018  

**Today's Progress**: Worked on learning how to use Getters and Setters

**Thoughts:** Cool to work on this concept again after really not understanding it when I first learned about `this` and getters and setters in college.  I'm going to work through the example projects tomorrow before doing Day 17's lesson.


**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Day 16 - Setters and Getters
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/tree/master/unit-1/Day_16_Getters%20and%20Setters)  

### Day 5: January 6, 2018  

**Today's Progress**: Redid yesterdays lesson from Codecademy

**Thoughts:** Ended up struggling to do the projects today so I redid the coursework from yesterday. This puts me a day behind schedule but the projects were much easier to complete after redoing the session.


**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Day 16 - Setters and Getters
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/tree/master/unit-1/Day_16_Getters%20and%20Setters)  

### Day 6: January 7, 2018  

**Today's Progress**: Did the Day 17 work from Codecademy

**Thoughts:** Worked on creating classes instead of objects and how to set up superclasses.  Found this lesson much easier to pick up than the previous one.  Also created a program that could be used to log media at a library.  


**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Day 17 - Classes
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/tree/master/unit-1/Day_17_Classes)  

### Day 6: January 8, 2018  

**Today's Progress**: Continuing to work on Minesweeper game  

**Thoughts:** Minesweeper game is coming along smoothly-- a lot of the time I feel like I'm just following the tutorial, but I've decided that that is part of learning it and I can come back to this again at the end of the course and see if it all makes sense then.  

**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Minesweeper game
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/unit-1/minesweeper/src/minesweeper.js)

### Day 7: January 9, 2018  

**Today's Progress**: Methods module from Codecademy

**Thoughts:** Can definitely see these being useful for data privacy and for keeping code from being compromised

**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Day 17 - Methods
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/unit-1/Day_19_Modules/Day%2019%20-%20Modules.md)  

### Day 8: January 11, 2018 << Was only able to code for 15 min yesterday before was interrupted, so counting it as a skip day.   

**Today's Progress**: Finished up the module lessons and also did the project about browser compatibility and transpilation.

**Thoughts:** Found both of these lessons to be pretty digestible.  The amount of different ways to export and import modules seemed like a lot to take in, but I imagine it's rare that developers use all of the different ways to import and export.

**Link to work:** [Codecademy: Build Front End Web Apps - Unit 1 - Day 17 - Methods
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/unit-1/Day_19_Modules/Day%2019%20-%20Modules.md)  
[Codecademy: Build Front End Web Apps - Unit 1 - Day 18 - Browser compatibility
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/unit-1/Day_20_Browser_Compatibilty/Day%2020%20-%20Browser%20Compatibility%20and%20Transpilation.md)  

### Day 9: January 12, 2018  

<center> <img src="/images/beerandcode.JPG" width="300px" /> </center>

**Today's Progress**: Did two days of Codecademy class as well as some work on a careers webpage for my company

**Thoughts:** Decided since it was friday to crack a beer and breeze through the next two days of my codecademy course.  We started a new unit on react, but the first two days are about the basics of HTML and CSS.  HTML and CSS are where I'm most comfortable so I was able to fly through the work today. (I didn't take any notes, so there's no commit from the class today).  

With the careers page I didn't make too much progress-- It's very frustrating because I have to work with an older CMS that doesn't allow for me to edit the stylesheet directly so the way I'm writing my code is pretty forceful in the sense that I have to overwrite a lot of code that exists.  In the end, there is a hard time constraint and limited flexibility on the CMS, so it's either doing it this way or having a careers page that looks straight out of the 90s.

**Link to work:** [Careers Landing Page](https://github.com/heyryanleys/Careers-Landing-Page)  

### Day 10: January 13, 2018  

**Today's Progress**: Did two more days of the Codecademy course i'm taking, both on React and JS

**Thoughts:** Pretty cool to start learning an entirely new framework. Today I banged out two more days of the course to catch up since I spent some extra time on methods and setters + getters.  A lot of JSX is simlar to HTML so it was fairly quick to pick up.  

**Link to work:** [Codecademy: Build Front End Web Apps - Unit 2 - Day 3 - Methods](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/unit-2/day-3-jsx-1/day-3-JSX-1.md)  
[Codecademy: Build Front End Web Apps - Unit 2 - Day 4 - Methods](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/unit-2/day-4-jsx-2/day-4%20-JSX-2.md)  
