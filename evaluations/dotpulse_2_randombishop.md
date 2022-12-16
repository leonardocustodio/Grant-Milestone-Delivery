# Evaluation



- **Status:** Pending
- **Application Document:** [DotPulse](https://github.com/w3f/Grants-Program/blob/master/applications/DotPulse.md)
- **Milestone:** 2
- **Kusama Identity:** randombishop (https://sub.id/5Gnixfp6vnznRkr91JgwkxYnCJCyHr8EaBzYfFsUKcTMzVYF)
- **Previously successfully merged evaluation:** [Milestone1](https://github.com/w3f/Grant-Milestone-Delivery/blob/master/deliveries/dotpulse-milestone_1.md)

| Number | Deliverable                                      | Accepted | Link                                                                                                                                                                                                                                                                                                                                             | Evaluation Notes                                                                                                                                  |
|-------:|--------------------------------------------------|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
|    0a. | License                                          | Yes      | [License](https://github.com/CrossChainLabs-DOT/dotpulse-webapp/blob/main/LICENSE)                                                                                                                                                                                                                                                               | MIT                                                                                                                                               |
|    0b. | Documentation                                    | Yes      | [API-docs](https://github.com/CrossChainLabs-DOT/dotpulse-api/blob/f3cf33274b9dbea3404e36faef4e3f01e496701e/docs.md), [Webapp-docs](https://github.com/CrossChainLabs-DOT/dotpulse-webapp/blob/main/README.md), [Video-demo](https://drive.google.com/file/d/1b0Mz9aIjra9NJDmaz_RVURbaLrXjnQnw/view?usp=sharing)                                 | Database schema. Video without sound                                                                                                              |
|    0c. | Testing and Testing Guide                        | Yes      | [API-test](https://github.com/CrossChainLabs-DOT/dotpulse-api/blob/f3cf33274b9dbea3404e36faef4e3f01e496701e/README.md), [Webapp-test](https://github.com/CrossChainLabs-DOT/dotpulse-webapp/blob/5f344e21291f86faa086f3e3619e1afef4cb9cd9/README.md) [Video](https://drive.google.com/file/d/1mb3vZqbavempMEbPxATmM77pqwOIND1P/view?usp=sharing) | All tests PASS. The number of tests is still minimal, in future iterations, would be nice to enrich the test suite with edge cases and bug cases. |
|    0d. | Docker                                           | Yes      | [Docker-file](https://github.com/CrossChainLabs-DOT/dotpulse-scraper/blob/3772a20347a19c05772ff907b8a53c085bef0515/docker-compose.yml)                                                                                                                                                                                                           | ?                                                                                                                                                 |


## General Notes

Good quality deliverable with clean code and all features worked at first try.

Improvement suggestions:

- The video without audio is not very helpful imo, 
would prefer a document that presents a high level introduction to the different components of the project and the dev frameworks used.

- Document the database schema.

- More tests (mainly edge cases and bugs as they're discovered)

