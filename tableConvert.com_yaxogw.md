| | PROD ENVIRONMENT             |                                                  | PRE ENVIRONMENT |                              |                                                       |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| | ---------------------------- | ------------------------------------------------ | --------------- | ---------------------------- |                                                       |
| | Key                          | Value                                            |                 | Key                          | Value |  |                                            |
| | ib:resource:op-co-code       | ib                                               |                 | environment                  | pre |  |                                              |
| | ib:account:service-offering  | i.e                                              |                 | ib:resource:type:backup      | FALSE |  |                                            |
| | company                      | Iberia                                           |                 | delete_after                 | Never |  |                                            |
| | ib:account:environment       | prod                                             |                 | ib:resource:application      | GTC997,GTC998,AVCD,CPC001,CPC002,ICA012,C77 |  |      |
| | ib:resource:apptype          | db                                               |                 | owner                        | iberia |  |                                           |
| | ib:resource:business-domain  | i.e                                              |                 | ib:resource:business-service | i.e |  |                                              |
| | ib:resource:business-service | i.e                                              |                 | project                      | iberia |  |                                           |
| | ib:resource:environment      | prod                                             |                 | typeproject                  | ib-cargo |  |                                         |
| | terraform                    | TRUE                                             |                 | company                      | Iberia |  |                                           |
| | ib:resource:environment-type | prod                                             |                 | terraform                    | TRUE |  |                                             |
| | ib:account:name              | workloads-prod-cargo                             |                 | map-migrated                 | mig47767 |  |                                         |
| | Name                         | xcpame2codb00003                                 |                 | Name                         | xcuame2codb00008 |  |                                 |
| | ib:resource:type:backup      | ec2                                              |                 | ib:resource:environment-type | pre |  |                                              |
| | typeproject                  | ib-cargo                                         |                 | group:component-grouping     | software-engineering--ib-dc-exit-cargo-db--infra |  | |
| | ib:account:short_name        | wsprodcargo                                      |                 | ib:resource:op-co-code       | ib |  |                                               |
| | environment                  | prod                                             |                 | ib:resource:apptype          | db |  |                                               |
| | map-migrated                 | mig47767                                         |                 | ib:account:service-offering  | i.e |  |                                              |
| | owner                        | iberia                                           |                 | sponsor                      | iberia |  |                                           |
| | ib:resource:name             | xcpame2codb00003                                 |                 | ib:resource:business-domain  | i.e |  |                                              |
| | ib:component:repo            | software-engineering--ib-dc-exit-cargo-db--infra |                 | ib:account:environment       | pre |  |                                              |
| | ib:resource:patch-policy     | patch-excepted                                   |                 | ib:account:name              | workloads-sdlc-pre-cargo |  |                         |
| | ib:resource:monitoring       | TRUE                                             |                 | ib:resource:patch-policy     | patch-excepted |  |                                   |
| | project                      | iberia                                           |                 | ib:resource:monitoring       | FALSE |  |                                            |
| | ib:resource:letter-ev        | p                                                |                 | ib:component:repo            | software-engineering--ib-dc-exit-cargo-db--infra |  | |
| | sponsor                      | iberia                                           |                 | ib:resource:name             | xcuame2codb00008 |  |                                 |
| | delete_after                 | Never                                            |                 | ib:resource:letter-ev        | u |  |                                                |
| | ib:resource:application      | GTC997,GTC998,AVCD,CPC001,CPC002,ICA012,C77      |                 | ib:resource:environment      | pre |  |                                              |
| | group:component-grouping     | software-engineering--ib-dc-exit-cargo-db--infra |                 | ib:account:short_name        | wsprecargo |  |                                       |