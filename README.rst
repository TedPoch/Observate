=========
Observate
=========
Functional Documentation (WIP)
------------------------
| Ted Pochmara
| Last Updated: 11 August 2018

Summary
-------
This is a rough draft of a design spec I am writing for a side project idea I'm
tossing around. One of our machine learning professors and I bemoaned the sad state of affairs in machine learning workflows; that is, the reliance on email and ad hoc solutions to record machine learning test setups and their results. He argued that many academics would be hard pressed to easily recreate and/or prove their research subsequent to publication. Which makes sense. Hell, I can't recognize my code two weeks after I write it...

Functional Requirements
----------------------
Interviewing Prof. Vivek and his PHD candidates at least, and possibly others in community (Reddit, SO, etc.).


* Create an unalterable experiment record for an executed DS/ML experiment
  * Record should include hardware variables
   * CPU, GPU, OS, driver and system versions
  * Record should include tooling and framework variables
   * Version of programming language (Java, Python, Scala)
   * Version of frameworks (Keras, TF, Theano, SciKitLearn, etc.)
   * Version of environment (JNotebook, Spark, Hadoop, Mongo, SQL)
  * Record should include program/process/script variables
   * Local variables/objects, expandable in some way (Keras Sequential)
   * Easily drill down to sub objects (Conv2D, Dense, Dropout) and their params
   * Global variables
     * need examples (may be able to roll this into one req for program vars
  * Record should include all results
   * This is going to be interesting...
* Application requires an web interface to easily search, analyze, and share experiment records



