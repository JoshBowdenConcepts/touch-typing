# Touch Typing

A free to use touch typing course for anyone who is interested in learing to touch type. The idea behind this is that there is nothing great that is free currently and this would be a way to give people access to something that is important for everyone to learn and to learn correctly.

I would like this project to utilize some external API to get randomized words for practice. Then we can even add in some strings that are not actually words to keep the user on their toes and typing correctly because the muscle memory should be letter based not word based. At least not entirely.

Things to do:
1. Research what word API's are out there to get words based on a string of characters. These will be used to practice typing.
2. Create the server that makes these requests based on an endpoint
    - There should be some randomization of the order that is returned so that the front end doesn't have to handle it.
    - There should be set patterns for learning the movements to and from the characters themselves.
3. Front end should be simple and easy to follow without needing to log in. Data could be persisted in either the cache, localStorage, or someother way that is decided upon.

Front End (Next.js)
BackEnd (TBD)
    
Reference: https://www.typingclub.com
