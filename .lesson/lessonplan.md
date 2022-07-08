# Lesson plan
  
---

```
h3 {
  text-align: center;
}

.flex-container {
  display: flex;
  height: 80px;
  background: peachpuff;
  border: 4px solid brown;
}


/* Edit below this line: */


/* Part 1 */
.one {
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}


/* Part 2 */
.two {
  flex-direction: column;
  align-items: center;
  justify-content: space-evenly;
}


/* Part 3 */
.three {
  flex-direction: row-reverse;
  justify-content: space-evenly;
  align-items: center;
}

.three :first-child {
  align-self: flex-start;
}

.three :last-child {
  align-self: flex-end;
}


/* Part 4 */
.four {
  flex-direction: column-reverse;
  justify-content: space-between;
  align-items: center;
}

.four :first-child {
  align-self: flex-end;
}

.four :last-child {
  align-self: flex-start;
}
```