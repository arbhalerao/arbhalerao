## OSS Contributions

### [redis/rueidis](https://github.com/redis/rueidis)  
*A fast Golang Redis client that supports Client Side Caching, Auto Pipelining, Generics OM, RedisJSON, RedisBloom, RediSearch, etc.*

- **PRs**
  - [Feature: Implemented LCS (Longest Common Substring) Command](https://github.com/redis/rueidis/pull/767)
  - [Bug: Ensure AUTH Command is Sent Before HELLO in NewClient Initialization](https://github.com/redis/rueidis/pull/791)
  - [Bug: Added SCORER and ADDSCORES Options to FT.AGGREGATE Command](https://github.com/redis/rueidis/pull/815)
  - [Perf: Consolidate wire, sc, mu slices into muxwire struct to reduce memory overhead](https://github.com/redis/rueidis/pull/869)

---

### [authzed/spicedb](https://github.com/authzed/spicedb)  
*Open Source, Google Zanzibar-inspired database for scalably storing and querying fine-grained authorization data.*

- **PRs**
  - [Feature: Support a WriteSchema dry-run](https://github.com/authzed/spicedb/pull/2491) (open)

---

### [DiceDB/dice](https://github.com/DiceDB/dice)  
*An open-source, fast, reactive, in-memory database optimized for modern hardware.*

- **PRs**
  - [Feature: Add APPEND Command to DiceDB with Redis-like Behavior, Tests, and Benchmarking](https://github.com/DiceDB/dice/pull/759)

- **Issues**
  - [Reported Inconsistent MSET Command Behavior](https://github.com/DiceDB/dice/issues/516)
  - [Reported another Inconsistent MSET Command Behavior](https://github.com/DiceDB/dice/issues/406)

---

### [p2-inc/keycloak-orgs](https://github.com/p2-inc/keycloak-orgs)  
*A Keycloak extension enabling single-realm, multi-tenancy for SaaS applications.*

- **PRs**
  - [Feature: Add attribute-based filtering to get organization count API](https://github.com/p2-inc/keycloak-orgs/pull/321)

- **Issues**
  - [Support attribute-based filtering](https://github.com/p2-inc/keycloak-orgs/issues/320)
  - [GET /invitations fails with 400 error when using admin-cli token](https://github.com/p2-inc/keycloak-orgs/issues/306)
