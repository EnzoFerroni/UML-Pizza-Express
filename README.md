# UML Pizza Express

[![UML](https://img.shields.io/badge/UML-modeling-FABD14)](https://www.uml.org)
[![GitHub Pages](https://img.shields.io/badge/docs-GitHub%20Pages-222222?logo=githubpages&logoColor=white)](https://enzoferroni.github.io/UML-Pizza-Express/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE.md)

Requirements and UML design for a pizza delivery chain that routes each order to the nearest kitchen and delivers in under 30 minutes.

## Table of Contents

- [About](#about)
- [Case Study](#case-study)
- [Contents](#contents)
- [Team](#team)
- [License](#license)

## About

Software modeling project for a UML course at Universidade Presbiteriana Mackenzie
(2023). The repository was created from the course template
[profdscrodrigo/UML-Classroom-FCI](https://github.com/profdscrodrigo/UML-Classroom-FCI);
the case analysis and every diagram were produced by the team. The documentation is
in Portuguese and is published at
**[enzoferroni.github.io/UML-Pizza-Express](https://enzoferroni.github.io/UML-Pizza-Express/)**.

## Case Study

Pizza-Express, a chain of 40 fast-food stores, lost 30% of its revenue after a
competitor started guaranteeing faster deliveries. The proposed answer is a network of
delivery-only kitchens placed close to customers, fed by a central ordering system.
Two systems were modeled:

- **Central system:** customer sign-up and login, ordering and payment, and finding the
  kitchen closest to the delivery address.
- **Franchise system:** receiving orders, preparing them and notifying the delivery
  partner when an order is ready.

## Contents

The [documentation](docs/index.md) covers:

- Functional and non-functional requirements
- Use case diagram and use case descriptions
- Sequence diagram
- Class diagram
- Component diagram and architecture decisions
- Deployment diagram

## Team

- Enzo Ferroni ([@EnzoFerroni](https://github.com/EnzoFerroni))
- Gabriel Pastorelli
- Rafael Neves
- Rodrygo Vasconcellos

## License

Released under the [MIT License](LICENSE.md), inherited from the course template.
