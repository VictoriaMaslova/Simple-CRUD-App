
### In this repository you will find how I implemented Three-layer abstraction architecture CRUD Application

* Controller Layer
* Service Layer
* DAL (via mongoose)


## Here is a structure of the project: 
```
src
│   index.js           # Entry point for application. Connecting to database MongoDB
└───Post.js            # Database models
└───router.js          # Express routes that define API structure
└───PostController.js  # Controller Layer
└───PostService.js     # Encapsulates all business logic
└───FileService.js     # Working with files

``` 
