# Homework 1
**Team members: Yihua Shi, Xueyan Wu**
<hr>

**1. Define the term essential difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an essential difficulty.**

As defined by Brooks, essential difficulties are the difficulties inherent in the nature of software, which includes the specification, design and testing of conceptual construct when building software. No matter how technique changes, there will still be essential difficulties shown in several ways - they could be conflicts of specifications between different regulations, or the ever-changing needs from clients. 
 
**2. Define the term accidental difficulties as it is used by Brooks. Provide background and context with your answer and at least one example of an accidental difficulty.**

Accidental difficulties are the difficulties related to the production of software but not inherent. These difficulties usually can be solved by technical improvements, such as bugs or crashes in software, syntax errors that can be checked and corrected by an IDE. When building a website with some frequently updated API, it is possible that our website fails to provide service all of a sudden due to the release of a newer version of that API. However, this can be easily fixed just by updating our code in accordance with its latest documentation.

**3. List and briefly describe the four essential difficulties of developing software systems that Brooks identifies. Provide additional examples of each type of the four essential difficulties.**

The four essential difficulties of developing software systems identified are *complexity*, *conformity*, *changeability* and *invisibility*.

***Complexity*** of developing software systems mostly comes from the large differences among numerous parts of software entities, the huge number of states, and the exponential increase in the number and types of different elements. One of the example problems deriving from complexity can be unreliability, like security loopholes and unstable service of the software due to unanticipated states.

***Conformity*** of developing software systems comes from the arbitrary environment where software exists and must conform to, this includes different interfaces, standards or regulations. Software has to comply with these external factors before it could work.
Example:
Whenever a large system such as a programming language updates, its current developers have to maintain the consistency of all interfaces of that system in order to guarantee the system still works properly.

***Changeability*** is the fact that software entity is constantly subject to change. The function of a software system is usually the part that has greater pressure of change, and people intuitively consider that software can be more easily changed in comparison with manufactured things. Moreover, successful software that survives longer than expected often needs to be adapted in order to work with modern environments.
Example:
At the beginning, WeChat was just a mobile app used for chatting. In order to keep up with the fast-paced changing environment, it has to develop the new features like payment functionality.

***Invisibility*** describes that software is invisible, unvisualizable and lack of graphical representation since it’s not inherently embedded in space. Even if we could try to diagram the software structure, it turns out that we need several graphs to depict different relationships. These graphs are less hierarchical, and are unlikely to be reduced or combined into a single diagram.
Example: 
We can not show the software architecture like using architecture plan in building bridges. So it’s really hard to show the solution to client and prove which one is a better solution than others.

**4. Define what Brooks means by a silver bullet and reconstruct his argument as to why he believes there is no silver bullet for software engineering.**

Brook defines a silver bullet as one single development that can make software costs drop rapidly and can deliver an order-of-magnitude improvement by itself in productivity, reliability and simplicity within a decade. 

Brook believes there’s no silver bullet for software engineering since it’s unlikely that the software progress could get an order-of-magnitude improvement for its very nature, especially when compared to the computer hardware progress which grows so fast. More importantly, we’re facing both essential and accidental difficulties when developing software technology, and the essential difficulties make it always hard to build software. To achieve the improvement in software development by a factor of 10, accidental difficulties have to dominate the overall effort and tools would need to be able to completely solve accidental difficulties. However, Brook doesn’t believe that either of the two hypothesis would come true.

**5. In lecture, software engineering's relationship to computer science was described by analogy by discussing the differences between a chemist (chemistry) and a chemical engineer (chemical engineering). Define software engineering and its relationship to computer science; make use of the chemist vs. chemical engineer analogy when answering this question.**

Computer science is about discovering scientific truth and principles about computational theory, identifying technologies and solving problems through math and science. Chemistry and computer science are very much alike in their nature since they’re both at the theoretical level, and are usually just experimented on a small scale.

In contrast, software engineering is more about “the application of engineering to the development of software in a systematic method”, as defined by Wikipedia[[1]](https://en.wikipedia.org/wiki/Software_engineering). It focuses more on applying the principles and technologies to solve practical problems in the context of constraints on a large scale. Similar to chemical engineering, it’s more dedicated to the delivery of real world application.

**6. In lecture, we discussed the importance of the following concepts to software engineers: abstractions, conversations, specification, translation, and iteration. Define each of these concepts as they are related to software engineering and discuss their importance.**

***Abstractions*** is a technique to hide the implementation detail of data and program and display them by their semantic meanings. It decreases the complexity of programs and let developers focus more on the important part.

***Conversations*** is the key in software development life cycle including analysis, design, implementation, testing, maintenance, etc. The engineers will have no idea what product to design if they don’t talk with the clients. The engineers can not fully understand how to call an API if there is no documentation about it. The engineers have to talk with testing team about which part goes well, which part needs to be fixed and modified. Without conversations, the software development can not continue. 

***Specification*** is reflected everywhere in software development life cycle. For requirement part, functional requirements, user requirements, etc should be specifically listed. For design part, a good engineer should write detailed high level design, low level design documentations. These documentations should be updated if the actual implementation changes. The advantage is it’s easier for the developer who is new to this project to know the progress and the detail design, technique to use, etc.

***Translation*** is embodied as the transition from one phase to another during the process of software engineering. Translation Other reflection of translation includes the delivery of functional and user requirements based on the client’s demand, or transformation from the design into real product with codes. Translation has its significance in the aspect of communication with different levels, and it helps understanding a large structure when it’s translated into smaller pieces.

***Iteration*** is reflected everywhere in software engineering as well. The engineers will not write 10000 lines of code in one sitting and then do debugging. Instead, the engineers will keep debugging and do testing during the implementation process. Iterative is also an important development model in industry environment. With adding new functional capabilities and modifying design at each iteration, the whole system can be developed through repeated cycles. 

# Reference 
1. https://en.wikipedia.org/wiki/Software_engineering
