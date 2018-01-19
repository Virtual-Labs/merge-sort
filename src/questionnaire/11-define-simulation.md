## Guidance
   The considerations for developing experiment simulations are:

   + Similarity to real life.

   + Real life data sets, ranges and processes available. 

   + Factor data needed for feedback, quality and productivty measurements.

   + Ease of understanding.

   + Simulation Model built.

   + Experiment procedure aligned to simulation model.

   + Elaborate procedure steps using available data - write requirements.

   + Define Work flow and failure resets.

   + Data for intermediate validations of sub processes.

   + Factor in exceptions/constraints.

   + Include all stakeholder functions - Admin, network, instructor, student.

   + Repeatability, reliability and fault tolerance considerations.

   + Scoring, quiz questions, marking, and other student evaluation aspects.

   + Network, bandwidth and failure mode scenarios.

   + Identify demo modules, test cases etc.
     
   Also refer to the guidance in the Simulation requirements step. 
     
For more details follow the [link](http://community.virtual-labs.ac.in/docs/ph3-new-exp-dev/).     

## Sample

   **Question 24** : How will the student _interact_ with
                     the experiment?  What are the "what-if"
                     scenarios that have been included in
                     the simulation?
   
   **Answer 24** : There will be a lab bench which holds the primitive
                  operations and the inputs that can used for the
                  experiment, it also has a 'lab floor' where
                  experiments happen when primitives and inputs are
                  dragged on the floor in a valid way.

                  Output of the experiment is shown on the screen and
                  student can record them for later use.

                 Experiments can be recorded and played back. This is
                 built using front-end technologies and use JS and
                 HTML5 so that it can work well on different form
                 factors like tablet and mobile.

  **Question 25** : What metrics will you use to _evaluate_
                   the student's extent of learning?


   **Answer 25** : 
                  
   		  1. Time spent on an activity
                  2. Correctness of output
                  3. Correctness of steps followed
                  4. How many times student attempted a problem
                     before getting it right.
