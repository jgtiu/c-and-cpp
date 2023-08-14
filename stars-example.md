```c
// prints i stars
void printIStars(int i) {
  // Count (call it j) from 1 to i (inclusive)
  for (int j = 1; j <= i; j++) {
    // Print a star
    printf("*");
  }
}

// prints a triangle of n stars
void printStarTriangle(int n) {
  // Count (call it i) from 1 to n (inclusive)
  for (int i = 1; i <= n; i++) {
    // Print i stars
    printIStars (i);
    // Print a newline
    printf("\n");
  }
}
```

# Meta
- I wrote this in Markdown because this C code won't run without some code to make it compile.

- Reference: Coursera. Writing, Running, and Fixing Code in C. Week 1. Step 5. Reading: Stars Example.