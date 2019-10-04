#Fragments
Reusable selection fo properties for a query. To declare them you must name it and define in which type it will work.
*** 
```
fragment userDetails on User {
  id
  firstName
  age
  company {
    id
    name
  }
}
```
***    