# Notes: C Structures (week-2-C Structures.pdf)

## C Structures Basics

- Definition: A collection of one or more variables, often of different types, grouped together under a single name
- Purpose: Organize related data items
- Comparison to Java: Similar to a Java class without methods (just fields)

## Structure Definitions

```c
struct card {
    char *face;
    char *suit;
};
```

## Self-Referential Structures

- Can include a pointer to the same structure type
- Example:
  ```c
  struct employee2 {
      char firstName[20];
      char lastName[20];
      unsigned int age;
      char gender;
      double hourlySalary;
      struct employee2 *ePtr; // pointer to same structure type
  };
  ```

## Typedef with Structures

- Purpose: Create aliases for structure types
- Example:
  ```c
  typedef struct {
      char *face;
      char *suit;
  } Card;
  ```

## Accessing Structure Fields

- Use the dot operator (.)
- Example: `var.name`, `var.id`, `var.GPA`

## Arrays of Structures

- Example: `Student studentList[30];`
- Accessing fields: `studentList[2].id = 12345678;`

## Pointers to Structures

- Create pointers using the & operator
- Dereference using the arrow operator (->)
- Example:
  ```c
  Player* pPlayer = &player1;
  pPlayer->score = 100;
  ```

## Exercises

1. Create a simple structure
2. Use typedef with structures
3. Implement nested structures
4. Pass structures to functions
5. Work with arrays of structures
6. Use pointers to structures

