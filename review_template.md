#### MC Question:
What is the right order for an if statement?

Options:
A) if (boolean) {code}
B) if {code} (boolean)
C) if {boolean} (code)
D) if 

Answer: A

---
#### MC Question:
What are the parameters for line()?

Options:
A) line(y, x, y1, x1)
B) line(y, x, length)
C) line(x1, y1, x2, y2)
D) line(x, y, length)

Answer: C

---
#### Programming question:
Write a function that draws a square cut in half by a line. The parameters should be the size and color. 
Possible solution:
```
void drawRect(int s, color c, color c1) {
  fill(c);
  rect(1, 1, s, s);
  stroke(c1);
  line(1, s / 2, 1 + s, s / 2);
}

