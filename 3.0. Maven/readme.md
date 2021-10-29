Maven - Mock interview Answers - https://youtu.be/5w8qVukxXXY 
--------------------------------------------------------------------------------------------------------------------------
```
5. when i issue mvn install what all things happen in background?
6. what are the settings you need to do before running mvn deploy?
7. why maven takes much time for 1st execution and from 2nd execution it will take less time?
```
ANSWERS
```
```

Maven  - Mock interview Answers - https://youtu.be/7WJ31VFk1_Y
--------------------------------------------------------------------------------------------------------------------------
```
5. what is multi module project in maven and what are the setting you want to do in multi module parent and child project? 
   what is dependency management?
7. what is transitive dependency?
```
ANSWERS
```
```

Maven
--------------------------------------------------------------------------------------------------------------------------
```
5. .m2 is local repository for maven, now I don’t want to use .m2 folder as my local repository I want to use some other folder as my local, 
   is it possible in maven? If yes, how would you do that?
==>  mvn install -Dmaven.repo.local=/alternate/repo/location 
6. maven follows convention over configuration that means it assumes code should be there under src/main/java, test cases under src/tests 
   and many more.Here my requirement is I don’t want to follow that conventions I need to use different folder structure is that possible in maven?
==> mvn help:effective-pom -Doutput=pom_eff.xml
7. What are dependency and plugin in maven? Give one example for each?
8. What are 3 build life cycles in maven?
9. In Which tag we will mention output artifact type( like jar, war or any other)?
```
ANSWERS
```
```

MAVEN
--------------------------------------------------------------------------------------------------------------------------
```
5. What are things you need to set, if you want download dependency from private repository ?
6. What are the issues you faced while working on maven projects?
7. Command to skip the test cases in maven
```

ANSWERS
```
```
