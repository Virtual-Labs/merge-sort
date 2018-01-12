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

   **Question 1** : How does the student interact with the experiment?
   
   **Answer 2** : There is a lab bench which holds the
                        primitive operations and the inputs that can
                        used for the experiment, it also has a 'lab
                        floor' where experiments happen when primitives
                        and inputs are dragged on the floor in a valid
                        way. 

 Output of the experiment is shown on the
                        screen and student can record them for later
                        use. 

 Experiments are recorded and played
                        back. This is built using front-end
                        technologies like JS and HTML5 so that it
                        works well on different form factors like
                        tablets and mobile devices.

  **Question 2** : What metrics are used to understand the students'
                   extent of learning?


   **Answer 2** : 
                  
   1. Time spent on an activity
                  2. Correctness of output
                  3. Correctness of steps followed 
                  4. How many times student attempted a problem before getting it right.
    
