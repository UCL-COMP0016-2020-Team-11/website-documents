# Research 

## Related Projects Review
#### For each of the similar projects, please list the project name, main features, and what you can learn from this existing application.
- The project done by the group last year.
- https://github.com/Apperta-IXN-for-the-NHS/IXN_Learning360 
- The group from last year built a web-based player, which the player is done in unity and the file management part is done with web utilities. 

## Technology Review
#### Please compare the possible solutions, describe what you choose, and explain why.
- Possible solution A: Just like the project done last year, we build the web app on electron and attach a unity player/editor to it.
>   Pros: The web-based website can be deployed on different machines.
>   Cons: There might be bugs involved when merging the 2 systems.
- Possible solution B: All parts of the project are done in Unity. 
>   Pros: Unity is open and flexible to changes. 
>   Cons: Unity itself is very complex and has different versions, so project built in old version of unity will have bugs when it is deployed into a newer version of unity.
#### Please compare the possible programming languages, frameworks, libraries, APIs, describe what you choose, and explain why.
- Unity can only use C# as its programming language. 
#### A summary of your technical decisions
- We decided to implement the whole project inside unity, so the project will be safer compared to web-based. Also, many NHS videos has its own GDPR regulation with it so it’s better to hold everything locally.

## References
