# Bloodhound Cypher Queries
Useful BloodHound Cypher Queries

Return all enabled users in the domain. If run in the neo4j window at localhost:7474 you can then export the results as JSON or CSV and parse as desired.   
`match (u:User {enabled: true}) return u`  
