## Features

1. Users can see the custom view of their code and contributions across all the repositories.
2. Try to run the extractoin of related packages etc. in backend.
3. Store the results so that it can be visualized.
4. Adjustable Dashboard.
5. Optional Ad button to support us.
6. Like Project , dislike or Love the project. (Bar visualisation)
7. Ability to Search Repository wise or multiple repository wise for a single user or multiple users
8. Make UI Dashboard with good Visuals
9. Fully Reactive Applications.
10. 1min contribution in any repository of the github.
11. Ability to engage viewer with realtime chat.
## Work Items:

- [ ] Make a Graphql Endpoint to see the result from github api graphql ( Use Spring Graphql )

- [ ] When a user opens the application and migrate to the site the application should give :

  - [ ] 1. Unified Search bar to see and search anything.
  - [ ] 2. Dashboard based on various customizations.

- [ ] Make a GraphQL Subscription Endpoint to see the results in the real time ( Neo4j + Spring Graphql)

- [ ] Make a Microservice

- [ ] Run a cron job (Spring batch) to take backup to multi cloud storages once a day

<del>
  <h2>
    Buy a domain and start working on it !!
  </h2> 
</del>

### Docker commands to run neo4j in background

docker run --hostname=d86982a9aa26 --mac-address=02:42:ac:11:00:02 --env=NEO4J_AUTH=neo4j/neo4j --env=PATH=/var/lib/neo4j/bin:/opt/java/openjdk/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin --env=JAVA_HOME=/opt/java/openjdk --env=NEO4J_SHA256=16cc236a08fd99acea9b08dc9b19c016dc693bb97fa4f4ca81c2c90cf9452292 --env=NEO4J_TARBALL=neo4j-community-5.6.0-unix.tar.gz --env=NEO4J_EDITION=community --env=NEO4J_HOME=/var/lib/neo4j --volume=/home/others/groovy:/home/groovy/scripts --volume=/data --volume=/logs --workdir=/home/groovy/scripts -p 7474:7474 -p 7687:7687 --restart=no --label='desktop.docker.io/wsl-distro=Ubuntu' --runtime=runc -d neo4j:5.6.0-community
