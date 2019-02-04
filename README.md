# JAVA Boot Camp

## Topic 0: Introduction to Object Oriented Programming Concepts

##### Reading:
1. Beginners: Java Concepts [basic tutorial][java-concepts] (in case you need it!)

2. Beginners: Have fun with [Introduction to Java Programming][introduction-to-java]. Do as much you can.

3. Beginners: [Access modifiers][java-access-control]

4. Beginners: [Operators][java-operators]

5. Beginners: [Collections][java-collections]

6. Beginners: [Collections cheat sheet][java-collections-cheat-sheet]

7. Explore: [Design Patterns][design-patterns]. Minimum scope: singleton, factory, abstract factory, strategy, template method, proxy, decorator and builder.

8. Explore: [Design Patterns Card][design-patterns-cheat-sheet]


##### Practice:
1. Create 4 classes applying inherithance with the follow structure:

- A Parent class implementing a method called whoIam which should return an String with his own name.

- B extends A and override the method whoIam.

- C extends A and override the method whoIam.

- D extends A but it doesn't override the methdo whoIam.

1.B Use an ArrayList to store all the classes, iterate and print to the console the return of the method whoIam.

2. Create 2 interface and 2 classes with the following structure:

- A Interface.

- B Interface.

- C implements A.

- D implements A and B.


2A. The methods on any implementation should print to console a String.


3. Create unit test or a java main class to execute the code.


## Topic 1: Maven / Git

##### Reading:
1. [What is Maven?][what-is-maven].

2. [Maven in 5 minutes][maven-in-5].

3. [maven lifecycle][maven-life-cycle].

4. [best practices][maven-best-practices].

5. [git-flow][gitflow]

##### Practice:
(It is assumed that Maven is already installed and working).

1. Create and build a simple Maven project:
2. Customize the Maven project by adding new dependencies: log4j, junit.
3. Create a simple unit test under src/test/java and run it. Then skip the unit test by property or by adding the skipping test configuration to your pom.xml file.

## Topic 2: Spring

##### Reading:
1. [Spring Home][spring-home]

2. [Spring projects][spring-projects]

3. [Spring core IOC][spring-core-ioc]

4. [Spring boot][spring-boot]

5. [Spring web mvc][spring-web-mvc]

6. [Spring developers tools][spring-developers-tool]

7. [Spring actuator][spring-actuator]

##### Practice:
1. Create a project including Spring Boot, inheriting from the spring boot parent pom, it should include
- spring-boot-starter-web
- spring-boot-starter-test
- spring-boot-devtools
- spring-boot-starter-actuator
2. The project should have a basic Rest Controller which should responde to a GET and a POST requests.

## Topic 3: Persistence

##### Reading:
1. [JPA][jpa]

2. [JPA Mappings][jpa-mappings]

3. [Hibernate][hibernate]

4. [Eclipselink][eclipselink]

5. [Spring data][spring-data]

6. 

##### Practice:
1. Include to the previous project
- spring-boot-starter-data-jpa
- connection driver
2. Get it running, map the entities and the entities needs to be generated in the database and requested through HTTP
3. Suggested structure of the project
packages: 
- com.<organization>.<nameofapplication>.model
- com.<organization>.<nameofapplication>.dao
- com.<organization>.<nameofapplication>.service
- com.<organization>.<nameofapplication>.rest

see:
[Maven Structure][maven-structure]
[Maven Layout][maven-layout]

<!-- Topic 0 OOP/JAVA  -->
[java-concepts]: https://docs.oracle.com/javase/tutorial/java/concepts/
[introduction-to-java]: https://www.ibm.com/developerworks/java/tutorials/j-introtojava1/
[java-access-control]: https://docs.oracle.com/javase/tutorial/java/javaOO/accesscontrol.html
[java-operators]: https://docs.oracle.com/javase/tutorial/java/nutsandbolts/opsummary.html
[java-collections]: https://docs.oracle.com/javase/8/docs/technotes/guides/collections/overview.html
[java-collections-cheat-sheet]: https://i.stack.imgur.com/EmzXy.gif
[design-patterns]: https://en.wikipedia.org/wiki/Software_design_pattern
[design-patterns-cheat-sheet]: http://www.mcdonaldland.info/files/designpatterns/designpatternscard.pdf

<!-- Topic 1 Maven/Git  -->
[what-is-maven]: https://maven.apache.org/what-is-maven.html
[maven-life-cycle]: https://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html
[maven-in-5]: https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html
[maven-best-practices]: https://books.sonatype.com/mvnref-book/reference/pom-relationships-sect-pom-best-practice.html
[gitflow]: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

<!-- Topic 2 Spring  -->
[spring-home]: https://spring.io/
[spring-projects]: https://spring.io/projects
[spring-core-ioc]: https://docs.spring.io/spring-framework/docs/current/spring-framework-reference/core.html
[spring-boot]: https://docs.spring.io/spring-boot/docs/current/reference/html/using-boot-build-systems.html
[spring-developers-tool]: https://docs.spring.io/spring-boot/docs/current/reference/html/using-boot-devtools.html
[spring-web-mvc]: https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html
[spring-actuator]: https://docs.spring.io/spring-boot/docs/current/reference/html/production-ready.html-

<!-- Topic 3 Persistence -->
[jpa]: https://www.oracle.com/technetwork/java/javaee/documentation/index.html
[jpa-mapping]: https://en.wikibooks.org/wiki/Java_Persistence
[hibernate]: https://hibernate.org/orm/documentation/
[eclipselink]: http://www.eclipse.org/eclipselink/documentation/
[spring-data]: https://docs.spring.io/spring-data/jpa/docs/current/reference/html/
[maven-structure]: https://maven.apache.org/guides/getting-started/
[maven-layout]: https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html
