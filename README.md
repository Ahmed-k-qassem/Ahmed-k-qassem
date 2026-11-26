## Ahmed Qassem

Software engineering student at Al Yamamah University in Riyadh. I mostly write backend code in Java and Spring Boot.

I like the boring-but-important parts: making sure bad input gets a clear error instead of a 500, making sure only the right people can see the data, and writing tests so I find the bug before someone else does.

Right now I'm finishing the backend for my university's Student Innovation Summit hackathon. It goes live in January 2027.

### Things I've built

**Student Innovation Summit registration API**
The hackathon site was running on Firebase, and I replaced it with a Spring Boot API on PostgreSQL. It handles sign-ups with Arabic and English error messages, stores project files on Cloudflare R2, and has a small admin side for the organisers. The repo is private for now. I'll publish the backend after the event.

**[Library Management System](https://github.com/Ahmed-k-qassem/Library_Management)**
My main Spring Boot practice project. It's secured with Keycloak and JWTs, and tested against a real MySQL database using Testcontainers. I also used it to learn how to move a codebase from package-by-layer to package-by-feature.

**[Hospital Management System](https://github.com/Ahmed-k-qassem/REPO-NAME)**
Built with plain Servlets, JSP and JDBC, no Spring. I wanted to see what a framework actually does for you. Writing transactions by hand and using `SELECT ... FOR UPDATE` to stop two patients booking the same slot taught me more than any tutorial.

### What I use

Java, Spring Boot, Spring Security, JPA/Hibernate, PostgreSQL, MySQL, Flyway, JUnit 5, Testcontainers, Docker, Git.

### Currently learning

How databases and Hibernate behave under the hood, and getting better at solving problems under time pressure.

