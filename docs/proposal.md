# Proposal: Structure and Interpretation of Incremental Stream Processing

Incremental stream processing is a widely researched area as it poses various challenges (such as, performance, compositionally, CPU and Memory usage, referential transparency). Different frameworks (e.g., Iteratee, Pipes, Conduit, Scalaz-Stream, Akka Streams) across variety of languages (e.g., Haskell, Scala) have been evolved to address these issues differently and with varying priorities.

In this comparative case study, we present different approaches to incremental stream processing. In particular, while basing foundation on the commonalities among these approaches and their primary constructs, we build a common ground and language to interact with their semantics. Afterward, we analyse and underscore what are the differences among the approaches, where they excel and where they fall short compared to the others, in addressing the core issues of stream processing.

As an audience, from the talk, I would get a comparative overview of varying approaches to incremental stream processing available in different programming languages, that potentially can help in differentiating them and selecting the right tool to get the job done.


## Other details
 
- *Target audience level*: Intermediate, Advanced
- *Authors*: Adil Akhter & Casper Konning 