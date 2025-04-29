# Proof-of-Concept - Assess PlantUML’s ability to model feature–component–control relationships.

This PoC demonstrates PlantUML’s ability to model feature–component–control relationships.

## Goals Checklist

- [x] Refactor a specific domain of a cybersecurity standard (e.g., CSA Safe App Standard - Authentication) into short, clear control statements.
- [x] Identify key components associated with the control statements.
- [x] Identify features or user stories associated with the key components.
- [ ] Bonus: Develop a styling guide

## Setup Instructions

Follow these steps to visualise the diagram:

1. Navigate to [PlantUML](https://plantuml.com/) or [PlantText](https://www.planttext.com/).
2. Copy the repository code into the editor's text field.
3. Render the diagram to view the feature–component–control relationships.

> **Note:** Refer to the [PlantUML MindMap syntax](https://plantuml.com/mindmap-diagram) for details on how to structure and extend mind map diagrams.

## Feature / Component Definition Guide 

Use the following set of questions to identify features and components:

"As a user, I want to make a request"

Feature: 
- What type of request is being made? (e.g., Sign-in request, Password reset request)

Component:
- What is required to initiate this request? (e.g., Password)
- What type of response will the user receive? (e.g. Notification, Confirmation message)
- What components are available to mitigate the request's potential threats? (e.g. fraud prevention)

## Contributing

Contributions are welcome and appreciated! If you have an idea or suggestion to improve this project:
- Fork the repo
- Create a feature branch
- Commit your Changes
- Push to your Branch
- Open a Pull Request
