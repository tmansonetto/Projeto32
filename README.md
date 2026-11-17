# Projeto32 – Counting Votes with a Map

A Java console exercise that tallies election votes from a CSV file using a `Map`.

## How it works
- The user enters the full path of a file where each line is `candidateName,votes`.
- The same candidate may appear on several lines; votes are accumulated in a `LinkedHashMap<String, Integer>`.
- The program prints each candidate with the total number of votes, in order of first appearance.

Example input:
```
Alex Blue,15
Maria Green,22
Bob Brown,21
Alex Blue,22
Maria Green,13
```
Output:
```
Alex Blue: 37
Maria Green: 35
Bob Brown: 21
```

## Run
Requires JDK 17+. Open the project in IntelliJ IDEA and run `application.Projeto32`, then type the file path when prompted.

## Concepts practiced
`Map` / `LinkedHashMap`, `BufferedReader`, `String.split`, try-with-resources.
