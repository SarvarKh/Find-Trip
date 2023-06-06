# capstone-project

Capstone Project at Epam UpSkill - Sarvar Khalimov

## FindTrip - Project by Sarvar Khalimov (Analysis and Design)
- What web app would it be? App to find suitable tours based on destination, duration, and price.
- Who is this project for? People who are willing to travel.
- What needs will it satisfy? It will help travelers save time and money: clients can use “FindTrip” instead of visiting tour agencies' offices. The platform will then find the best matching offers of agencies and show them to travelers. Clients can compare and decide which tour agency to approach while saving time.

### Step #1 - (Functional) Requirements.
The system must:
Allow travelers to find tours based on the destination, duration, and budget.
Allow travelers to see available tours (around 10) on the home page with an agency rating.
Allow travelers to order tours.
Allow travelers to rate tour agencies.
Allow travelers to see their order page.
*2nd part to implement later as the project progresses:
Allow travelers to signup and log in. Allow agencies to signup and login. Allow agencies to add tours: destination, duration, price, (*photo/video via hyperlinks to youtube). Allow an agency to edit or delete tours
Non-functional Requirements:
credible orders, users, and touristic agencies.
available 24/7

### Step #2 - Descriptions.
Use case No.1
Title: Order optimal tour
Primary Actor: Traveler
Success scenario: Traveler visits the “FindTrip” website. On the home page, travelers can see around 10 tours. Then, the traveler enters the tour destination, duration, and budget. Platforms searches and provides available options from tour agencies. Traveler selects the most suitable tour and orders it. Order will appear traveler’s bag.
Use case No.2
Title: Rate tour agency
Primary Actor: Traveler
Success scenario: Traveler visits the “FindTrip”. Then, the traveler enters the tour destination, duration, and budget. Platforms searches and provides available options from tour agencies. Traveler selects the most suitable tour and orders it. Rate agencies. Rate of agency changes.

*2nd part to implement later as the project progresses:
Use cases to implement later: Traveler signup and login, Agency signup and login, Agency adding tour, Agency editing or deleting tour.

### Step #3 - Identifying objects (conceptual model).
Objects as nouns: Traveler, FindTrip” website, home page, tours, destination, duration, budget. Platforms, options, tour agencies, order, bag.

### Step #4 - Interactions between objects (write down nouns from step #3 around circle and connect objects with each other if they have direct relationships. Finally, we mark these connections with verbs):

<div align="center">
  <img src="image/Interactions.png?raw=true" width="100%" height="auto"/>
</div>

### Step #5 - Create class diagram. This step comprises a few sub-steps: Identifying class responsibilities, CRC cards, and creating a class diagram itself.

1. Identifiying class responsibilities
- see around 10 tours
- enters/selects the tour destination, duration, and budget
- searches and provides available options from tour agencies
- selects the most suitable tour and orders it
- order will appear traveler’s bag.

2. CRC cards: Class, Responsibility, Collaboration

<div align="center">
  <img src="image/crc_card.png?raw=true" width="100%" height="auto"/>
</div>

3. Creating class diagram: attributes and behaviors

<div align="center">
  <img src="image/class_diagram.png?raw=true" width="100%" height="auto"/>
</div>

