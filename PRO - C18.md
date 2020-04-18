**PRO - C18**



**Unwanted Code**

```javascript
if(localStorage["HighestScore"] < score){
    
    localStorage["HighestScore"] = score;
  }
  

console.log(localStorage["HighestScore"]);
```



**Fixed Code**

```javascript
Before: obstacle.lifetime = 300;
After: obstacle.lifetime = 100;
Due to longer duration the program will use more memory, hence, the lifetime is shortened.

before: cloud.lifetime = 200;
after cloud.lifetime = 300;
Clouds tends to dissapear before it exits the screen; as a result, limetime is elongated.
```