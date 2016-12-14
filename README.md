# Microservices CICD Interview Problem

Write a simple microservice that calculates the [Euclidean distance](https://en.wikipedia.org/wiki/Euclidean_distance) between a pair of two dimensional points.

## Requirements
1. Written in one of the following languages (Java/Scala/Groovy/Go/Python)
2. REST based
3. CICD process which produces a runnable Docker image containing the service

### Example Request Format
```
{
  "p1": {
    "x": 0,
    "y": 0
  },
  "p2": {
    "x": 3,
    "y": 4
  }
}
```

### Example Response Format
```
{
  "distance": 5
}
```
