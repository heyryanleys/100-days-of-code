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

**Link to work:** [Codecademy: Build Front End Web Apps - Minesweeper game
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/minesweeper/src/minesweeper.js)  

### Day 1: January 2, 2018  

**Today's Progress**: Took notes about control flows, built a magic 8 ball app and an app that tells racers their start time based on their age the time they registered.

**Thoughts:** Thought this was much easier than yesterday-- I've used if else statements a lot in the past so the class part of today was pretty easy, although I didn't know about switch statements which seem very useful.

**Link to work:** [Codecademy: Build Front End Web Apps - Day 13
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/tree/master/Day%2013%20-%20Control%20Flow)  

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

**Link to work:** [Codecademy: Build Front End Web Apps - Minesweeper game
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/minesweeper/src/minesweeper.js)  

### Day 3: January 4, 2018  

**Today's Progress**: Did yesterdays lesson from Codecademy again today

**Thoughts:** Had an easier time than yesterday but still having a tough time with this one, I have to move on to the next lesson tomorrow to not get behind, but I want to come visit this in a few days and see if the next lessons help me understand this one better.


**Link to work:** [Codecademy: Build Front End Web Apps - Minesweeper game
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/minesweeper/src/minesweeper.js)  

### Day 4: January 5, 2018  

**Today's Progress**: Worked on learning how to use Getters and Setters

**Thoughts:** Cool to work on this concept again after really not understanding it when I first learned about `this` and getters and setters in college.  I'm going to work through the example projects tomorrow before doing Day 17's lesson. 


**Link to work:** [Codecademy: Build Front End Web Apps - Day 16 - Setters and Getters
](https://github.com/heyryanleys/Codecademy-Build-Front-End-Web-Apps/blob/master/Day%2016%20-%20Getters%20and%20Setters/Day%2016%20-%20Objects.md)  
