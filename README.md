## Hi, I'm Peterson 👋

**Senior Software Engineer** with 12+ years building backend systems for **fintech, payments, identity and compliance**.

Currently working on **Coinbase** projects (via Turing), on the Identity, Onboarding & Compliance platform, helping decompose a legacy Ruby on Rails monolith into domain-driven Go microservices. Previously at **iFood (MovilePay)** and **PagBank**, and formerly served as **Tech Lead of a Clojure team** on a part-time contract.

- 🔐 **Domains:** KYC, CDD/EDD, AML/risk, GDPR data privacy, payments, monolith decomposition, feature-flagged migrations
- 📈 **Impact:** contributed to compliance automation efforts that significantly reduced operating overhead at Coinbase; led a migration off third-party automation tools that saves **R$1M+/year** for a Brazilian media company
- 🌱 **Open source contributions:**
  - [ai-memory](https://github.com/akitaonrails/ai-memory) (Rust): long-term memory and handoffs between AI coding agents
  - [Pedestal](https://github.com/pedestal/pedestal) (Clojure): a framework for building web services and APIs
- 🤖 **AI-assisted engineering:** Cursor, Claude Code, MCPs and multi-agent workflows for legacy discovery, planning and code review
- 🌎 Based in Brazil (UTC-3) · English C1

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/peterson-salme) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:petersonsalme@gmail.com)

## 🛠️ Tech Stack

- **Languages**<br>
  ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) ![Clojure](https://img.shields.io/badge/Clojure-%235881D8.svg?style=for-the-badge&logo=clojure&logoColor=white)
- **Backend & messaging**<br>
  ![gRPC](https://img.shields.io/badge/gRPC-%23244c5a.svg?style=for-the-badge&logo=google&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
- **Data & infra**<br>
  ![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

## 🚀 Side Projects

Study projects I keep as reference implementations. My production work is in private company repositories.

- [**grpc-microservices**](https://github.com/petersonsalme/grpc-microservices): Go services for auth, products and orders behind a Gin REST API gateway, talking over gRPC/Protobuf, with JWT auth, one logical Postgres database per service and a single `docker-compose up` to run it all.
- [**rest-api-with-jwt**](https://github.com/petersonsalme/rest-api-with-jwt): Go REST API with short-lived access tokens and refresh tokens that can be revoked (tracked in Redis), a check that rejects unexpected signing algorithms, an OpenAPI 3 spec and tests.
- [**microservices-for-java-developers**](https://github.com/petersonsalme/microservices-for-java-developers): polyglot services (Spring Boot, MicroProfile/Thorntail, Node.js) behind an Apache Camel gateway that calls them in parallel, based on the book by Benevides & Posta.
- [**blockchain-with-go**](https://github.com/petersonsalme/blockchain-with-go): a minimal blockchain with SHA-256 linked blocks, chain validation and a longest-chain rule, with a README on the trade-offs of skipping P2P networking and PoW/PoS.
