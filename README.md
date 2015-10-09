# Nag
##instructions on how to nag

### I know someone who worries too much.

1. Asking an array of questions which one is most concerned or anxious over.
```processing
  String[] commonQuestions = {
    "Are you going to the dentist?", 
    "Do you want to eat with us?", 
    "Have you switched your \n insurance plan yet?", 
    "Have you spoken \n with your sister?"
  };
```

2. You are in a fairly good relationship with the other person. 


3. And that person is still alive.


4. That other person will continuely ask the same series of question. 
```processing
text(question, width/2, height/2);  
```

5. Whether I answer yes or no, that other person will always ask the same series of questions repeatedly. 
```processing
if( (passedTime > totalTime) && (passedTime < totalTime2) ){
        // background(0,0,255);
    text(usualResponse, width/2, 2*height/3);
   } else if ((passedTime > totalTime2) && (passedTime<totalTime3)) {
        println(angryResponse);
        text(angryResponse, width/2, 2*height/3);
    }
        
  ```
