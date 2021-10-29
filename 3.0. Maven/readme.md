Maven - Mock interview Answers - https://youtu.be/5w8qVukxXXY 
--------------------------------------------------------------------------------------------------------------------------
```
- when i issue mvn install what all things happen in background?
- what are the settings you need to do before running mvn deploy?
- why maven takes much time for 1st execution and from 2nd execution it will take less time?
```
ANSWERS
```
```

Maven  - Mock interview Answers - https://youtu.be/7WJ31VFk1_Y
--------------------------------------------------------------------------------------------------------------------------
```
- what is multi module project in maven and what are the setting you want to do in multi module parent and child project? 
   what is dependency management?
- what is transitive dependency?
```
ANSWERS
```
```

Maven
--------------------------------------------------------------------------------------------------------------------------
```
- .m2 is local repository for maven, now I don’t want to use .m2 folder as my local repository I want to use some other folder as my local, 
   is it possible in maven? If yes, how would you do that?
==>  mvn install -Dmaven.repo.local=/alternate/repo/location 
- maven follows convention over configuration that means it assumes code should be there under src/main/java, test cases under src/tests 
   and many more.Here my requirement is I don’t want to follow that conventions I need to use different folder structure is that possible in maven?
==> mvn help:effective-pom -Doutput=pom_eff.xml
- What are dependency and plugin in maven? Give one example for each?
- What are 3 build life cycles in maven?
- In Which tag we will mention output artifact type( like jar, war or any other)?
```
ANSWERS
```
```

MAVEN
--------------------------------------------------------------------------------------------------------------------------
```
- What are things you need to set, if you want download dependency from private repository ?
- What are the issues you faced while working on maven projects?
- Command to skip the test cases in maven
```

ANSWERS
```
```
