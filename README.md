# cit281-p6

# Project 6: Shape Perimeter Calculator Server

### Overview
In this project I used javascript to create a calculator that takes input of shapes with side lengths and outputs the perimeter. In this project I also gained experience using methods such as reduce() and super()
### Project Code
```markdown
class Shape {
    constructor(sidesArray) {
        this.sides =  sidesArray;
    }
    perimeter() {
        let output = 0;
        for (let i=0; i < this.sides.length; i++) {
            output = output + this.sides[i];
        }
        return output;
    }
  }


//console.log(new Shape([5, 10]).perimeter());  // 15
//console.log(new Shape([1, 2, 3, 4, 5]).perimeter()); // 15
//console.log(new Shape().perimeter()); // 0

class Rectangle  extends Shape {
    constructor(length, width) {
        
    }

    perimeter() {
        let output = 0;
        for (let i=0; i < this.sides.length; i++) {
            output = output + this.sides[i];
        }
        return output;
    }
  }


//console.log(new Rectangle(4, 4).perimeter());  // 16
//console.log(new Rectangle(4, 4).area());  // 16
//console.log(new Rectangle(5, 5).perimeter()); // 20
//console.log(new Rectangle(5, 5).area()); // 25
//console.log(new Rectangle().perimeter()); // 0
//console.log(new Rectangle().area()); // 0


class Triangle extends Shape {
    constructor(sideA, sideB, sideC) {
        
    }
    
    perimeter() {
        let output = 0;
        for (let i=0; i < this.sides.length; i++) {
            output = output + this.sides[i];
        }
        return output;
    }
  }
```
