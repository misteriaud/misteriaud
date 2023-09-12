## What to say?
Aspiring software engineer and former cinema/television sound mixer.
Self-taught coder since childhood and currently learning computer science concepts and development best practices at [42school](https://42.fr/en/homepage/).
Interests in networking (especially distributed), audio signal processing and machine learning.

## More about me

<details>
  <summary>Skills</summary>

### Soft skills
- Committed to a methodical approach (don't like to jump right into coding to end up with spaghetti code).
- Emphasis on effective team communication.

### Hard skills
#### Languages
- **C** and **C++**: memory allocation, I/O system calls, parallelism, and concurrency implementations.
- **Python**: used only for small tools projects.
- **Typescript**: used for many side-projects.

#### Useful knowledge
- Basic Linux administration knowledge (installation, package installation, `sudo` authorization).
- `Makefile` writing.
- `Dockerfile` and `docker-compose.yml` writing.
- Skills in domain name and cloud administration (e.g., running instances, setting up load-balancer, "serverless" functions).

#### Next on my learning list
I'm interested in these techs:
- **Rust**: to work on distributed safe software, and to learn WASM concepts.
- **Elixir**: `BEAM VM` appears to be powerful, and the Elixir functional programming paradigm attracts me.

***
</details>

<details>
  <summary>Relevant projects</summary>


### School projects
> Each of the following projects was developed either by myself or in a team.

| Project Name                                                           | Description                                                                                                                                                                                                                                                                                                                                                                                                    | Knowledge acquired                                                                                                                                                                                                           |
| ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**Minishell**](https://github.com/misteriaud/42_minishell)            | Implementation from scratch in **C** of a `bash` interpreter.                                                                                                                                                                                                                                                                                                                                                  | - Unix system calls (`fork`, `pipe`, `signal`, `stat`, `execve`, ...)<br/>- Parallel execution.                                                                                                                              |
| [**Containers**](https://github.com/misteriaud/42_ft_containers)       | Homemade implementation in **C++** of some STL containers (`std::vector`, `std::map`, `std::set`, `std::stack`) using memory management and `RBTree` under the hood.                                                                                                                                                                                                                                          | - Object-oriented abstractions.<br/>- Data-structures insertion/deletion/retrieval complexity.<br/>- Unit-testing development.                                                                                               |
| [**Webserv**](https://github.com/ouafabulous/webserv_42)               | Fully configurable home-made web server in **C++** (following `HTTP/1.1` RFC). Implementing IO concurrent design pattern to serve as many successful requests as possible (`GET`/`POST`/`DELETE` files, directory listing, `CGI` execution).                                                                                                                                                                   | - TCP connections via system calls (`epoll`, `socket`, `accept`, `listen`, `send`, `recv`, ... ) <br/>- Event-driven architecture and concurrent computing.<br/>- RFC/Protocols understanding.<br/>- Fault-tolerance design. |
| [**ft_transcendence**](https://github.com/misteriaud/ft_transcendence) | `Docker-compose` deployable webgame. Featuring social-networking mechanisms (friendships, direct-messages, profile pictures), real-time multiplayer good old *Pong*, chatroom with administration roles. Authentication using `OAuth2` (through *42school* provider) and `2FA-TOTP` implementation. Built on top of `NestJS` as backend, `PostgreSQL` as DB, `Prisma` as ORM and `ReactJS`/`Tailwind` as frontend. | - `REST API` concepts.<br/>- Websockets.<br/>- Interface between `NestJS` Object-oriented data-structure and `PostgreSQL` relational database via `Prisma`.<br/>- Authentication and authorization standards (`OAuth2`, `JWT`, `Password hashing`, `TOTP`).                                                                                                                                                                                                                               |

### Side projects
- **CyberClub**: online cinema club for sharing underground movies with my friends and family during the pandemic.
- Several professional tools for dubbing recording.
- Made contributions to the open-source [**QuickAdd**](https://github.com/chhoumann/quickadd) obsidian.md plugin via pull/request.

***
</details>
