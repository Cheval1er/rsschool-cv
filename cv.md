![Nutsa](https://user-images.githubusercontent.com/80838206/161750908-446c43c1-8b56-44f1-b869-73a4a8df7867.jpeg)

# Nutsa Matchavariani
----------
### Contacts:
- **Discord:** Chevalier#0573
- **E-mail:** _nutsa.matchavariani.1@gmail.com_
- **Tel:** +995595121314
- **Facebook:** [Nutsa Matchavariani](https://www.facebook.com/Cheval11er)

### About myself:  
Experienced Lecturer with a demonstrated history of working in various universities. With Master Degree in **Mathematics** and **Economics**. Until now, programming was my hobby, because I enjoy this activity and I like it, I want to make it a major profession. At the same time I want to prove that becoming a skilled programmer depends on your desire and diligence and not on age. My goal is to become a full stack developer.

### Skills:
 ##### **Fundaments of**: 
   - HTML;
   -  CSS;
   -  JS

### Code example:
```javascript
var DELAY = 1000;
var CIRCLE_RADIUS = 25;
var BUFFER = 50;
var square;
var circle;
var xStart = 0+50;
var xFinish = getWidth() -50;
var yStart = 0+100;
var yFinish = getHeight(); -100;
var numShapes = 1;
function start() {
setTimer(drawShapes, DELAY);
}
function drawCircle(){
circle = new Circle(CIRCLE_RADIUS);
circle.setPosition(Randomizer.nextInt(50, getWidth()-50), Randomizer.nextInt(50, getHeight()-50));
circle.setColor(Randomizer.nextColor());
add(circle);
}
function drawSquare(){
square = new Rectangle(50,50);
square.setPosition(Randomizer.nextInt(50, getWidth()-100), Randomizer.nextInt(50, getHeight()-100));
square.setColor(Randomizer.nextColor());
add(square);
}
function drawShapes(){
if(numShapes%2==0){
for(var i=0;i<numShapes;i++){
var newX = Randomizer.nextInt(xStart, xFinish);
var newY = Randomizer.nextInt(yStart, yFinish);
drawCircle(Color, newX, newY);
}
}else{
for(var i=0;i<numShapes;i++){
var newX = Randomizer.nextInt(xStart, xFinish);
var newY = Randomizer.nextInt(yStart, yFinish);
drawSquare(Color, newX, newY);
}
}
numShapes=numShapes+1;
}
```

### Work experience:
*Nothing yet in this field...*

### Education and courses:
1. Internationas School of Economics
2. Ilia State University - MA in Mathematics
3. Bitcamp JS fundaments https://codehs.com/student/3008821/section/204244/assignments
4. JS, CSS, HTML https://www.udemy.com/course/the-ultimate-fullstack-web-development-bootcamp/
5. FreeCodeCamp Responsive Web Design https://www.freecodecamp.org/certification/mrks77/responsive-web-design


### Language:
- Georgian - Native
- German - Upper Intermediate 
- English - Upper Intermediate
- Russian - Intermediate
