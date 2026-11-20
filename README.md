Hi, I'm Ayoub, a backend engineer and a student at [1337](https://1337.ma) (the 42 Network) in Morocco.

I like the parts of a system nobody sees: queues, sandboxes, query plans, and the tests that prove they hold. These days that means TypeScript, NestJS, PostgreSQL, Redis and Docker; before that it was C and C++ at 42.

### What I'm building

**[CodeArena](https://github.com/Ayoubioussoufa/codearena)**: a competitive programming platform with its own judge. Submissions go through a BullMQ queue to a worker that runs each one in a locked-down Docker container: no network, a read-only filesystem, every capability dropped, memory and PID limits. Six attack programs run against the sandbox in CI. NestJS, Next.js, PostgreSQL, Redis.

**[CyberDojo](https://github.com/Ayoubioussoufa/cyberdojo)**: a cybersecurity course from zero to Master's level, on the web ([live demo](https://cyberdojo-beta.vercel.app)) and as a desktop app whose AI tutor runs on your own machine.

Next for CodeArena: deployment with HTTPS and CI/CD, then an AI hint for failed submissions, on a self-hosted model with retrieval over my own notes and evals that run in CI.

### From 42

- [Webserv](https://github.com/Ayoubioussoufa/Webserv): an HTTP/1.1 server in C++98, with CGI
- [Minishell](https://github.com/Ayoubioussoufa/Minishell): a Unix shell in C, with pipes, redirections and environment variables
- [Inception](https://github.com/Ayoubioussoufa/Inception): NGINX, WordPress and MariaDB, each in its own Docker image, wired with Compose
- [Philosophers](https://github.com/Ayoubioussoufa/Philosophers): the dining philosophers, with threads and mutexes

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/ayoubbioussoufa/) · [LeetCode](https://leetcode.com/u/01082023/)

[![LeetCode stats](https://leetcard.jacoblin.cool/01082023?theme=dark&font=Ubuntu)](https://leetcode.com/u/01082023/)
