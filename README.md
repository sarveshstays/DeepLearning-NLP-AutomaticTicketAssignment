# DeepLearning-NLP-AutomaticTicketAssignment
The objective of this is to build an automatic ticket assignment system using natural language processing capabilities of machine learning. This will address the key issue of current manual review and assignment of tickets to appropriate person that is currently consuming lot of time and effort. 


Business Domain Value
In the support process, incoming incidents are analyzed and assessed by organization’s
support teams to fulfill the request. In many organizations, better allocation and effective usage
of the valuable support resources will directly result in substantial cost savings.
Currently the incidents are created by various stakeholders (Business Users, IT Users and
Monitoring Tools) within IT Service Management Tool and are assigned to Service Desk teams
(L1 / L2 teams). This team will review the incidents for right ticket categorization, priorities and
then carry out initial diagnosis to see if they can resolve. Around ~54% of the incidents are
resolved by L1 / L2 teams. Incase L1 / L2 is unable to resolve, they will then escalate / assign
the tickets to Functional teams from Applications and Infrastructure (L3 teams). Some portions
of incidents are directly assigned to L3 teams by either Monitoring tools or Callers /
Requestors. L3 teams will carry out detailed diagnosis and resolve the incidents. Around ~56% 
of incidents are resolved by Functional / L3 teams. Incase if vendor support is needed, they will
reach out for their support towards incident closure.
L1 / L2 needs to spend time reviewing Standard Operating Procedures (SOPs) before
assigning to Functional teams (Minimum ~25-30% of incidents needs to be reviewed for SOPs
before ticket assignment). 15 min is being spent for SOP review for each incident. Minimum of
~1 FTE effort needed only for incident assignment to L3 teams.
During the process of incident assignments by L1 / L2 teams to functional groups, there were
multiple instances of incidents getting assigned to wrong functional groups. Around ~25% of
Incidents are wrongly assigned to functional teams. Additional effort needed for Functional
teams to re-assign to right functional groups. During this process, some of the incidents are in
queue and not addressed timely resulting in poor customer service.
Guided by powerful AI techniques that can classify incidents to right functional groups can
help organizations to reduce the resolving time of the issue and can focus on more productive
tasks

Milestone 1: Pre-Processing, Data Visualisation and EDA
Overview
● Exploring the given Data files
● Understanding the structure of data
● Missing points in data
● Finding inconsistencies in the data
● Visualizing different patterns
● Visualizing different text features
● Dealing with missing values
● Text preprocessing
● Creating word vocabulary from the corpus of report text data
● Creating tokens as required 


Milestone 2: Model Building
Overview
● Building a model architecture which can classify.
● Trying different model architectures by researching state of the art for similar tasks.
● Train the model
● To deal with large training time, save the weights so that you can use them when
training the model for the second time without starting from scratch.


Milestone 3: Test the Model, Fine-tuning and Repeat
Overview
● Test the model and report as per evaluation metrics
● Try different models
● Try different evaluation metrics
● Set different hyper parameters, by trying different optimizers, loss functions, epochs,
learning rate, batch size, checkpointing, early stopping etc..for these models to finetune them
● Report evaluation metrics for these models along with your observation on how
changing different hyper parameters leads to change in the final evaluation metric.


