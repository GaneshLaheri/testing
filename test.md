## Turbot Concepts
Turbot provides enterprise guardrails for Amazon Web Services.

This document outlines the beliefs, models and assumptions Turbot has defined
to create those guardrails - providing organizations with a working balance
between agility and compliance. Please see [other help sections](https://help.github.com) for
implementation specifics and how to guides.

## Design Beliefs
Balancing agility with controls requires a clear and simple set of beliefs
guiding our designs and trade-off decisions. This section outlines how
Turbot thinks about Enterprise Controls for Cloud Infrastructure.

Cloud Infrastructure is managed dynamically by Applications & DevOps Teams.
Cloud Infrastructure is designed to be changed in real time,
providing scalability and reliability in Production and flexibility in
Development. Enterprises moving to Cloud Infrastructure need to give control of
Application Infrastructure to the Application and its DevOps Teams.

Enterprises run many different Applications.
Each Enterprise consists of many Applications, each with a specific purpose,
requirements and controls. Applications may interact, or be dependent on each
other, but are managed (e.g. access, change control) as separate systems.
