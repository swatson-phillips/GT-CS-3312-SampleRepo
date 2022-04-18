# Detailed Design Component and Data Design Feedback
Please see in-line comments and reach out if you'd like help.

I am available to meet and discuss if you have questions.

## Component Design
### Resources
* Checkout this 2340 video on Class diagrams: https://youtu.be/FjYYOmUQOO4
* Checkout this 2340 video on Sequence diagrams: https://youtu.be/ONnT69-eBHQ
* Visual Paradigm tutorial on class diagrams: https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-class-diagram/ (Links to an external site.)
* Visual Paradigm tutorial on robustness diagrams: https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-class-diagram/ (Links to an external site.)
* Visual Paradigm tutorial on component diagrams: https://www.visual-paradigm.com/guide/uml-unified-modeling-language/what-is-component-diagram/

### General
* You are lacking conceptual integrity between the different view presented. Also see in-line comments.

* It looks like you have given me 2 dynamic views of your system. Make sure that you have given me 1 static (on-runtime) view and 1 dynamic view of your system and both give more detail than the system architecture.

### Static
* Remember that static means structure not runtime/flow. Make sure you are only showing dependency and composition and not dipping into runtime interaction, it can be easy to slip into that

## Data Design
* This is not just about the DB. How are you making API calls? How are you getting information in and out of the DB. Please provide information and examples.
* While this is good (security related) information, consider putting it in its own sections. This section is supposed to be about data exchange. Are you using any APIs, how are you getting information in and out of your DB and System. How are you transferring data?
* What are your foreign keys? How are the relationship and cardinality maintained?
* This is a NoSQL non-relational DB, why did you pick an entity RELATIONAL database diagram? Giving the JSON scheme and example data would be far more effective.
