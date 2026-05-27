---
project_name: fastapi-realworld-backend
last_updated: 2026-02-01
current_version: 0.1.0
semantic_versioning: true
---
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- latest-entry-marker -->
## [0.1.0] - 2026-02-01

### Recent Activity
- minor change to setup workflow (08c6479)
- Update README (5eaebc4)
- ignore test cache (6e46f24)
- Remove demo.md from .gitignore and set test environment in conftest.py (1faf26d)
- Remove Docker/Alembic infrastructure and clean up development configuration (b778f3c)
- Update seed script to prevent duplicate data and change frontend API URL (c5bbc76)
- Add follower relationships to seed script for Your Feed functionality (410b647)
- Fix SQLite compatibility issues found during local testing (88aaa09)
- Migrate from PostgreSQL to SQLite (e0bc986)
- clean git status (f51deb0)
- minor updates (1c0e82e)
- Add default value for secret_key to simplify setup (b0bc281)
- Refactor to use SQLite instead of PostgreSQL/Docker (717e442)
- add frontend files (179bcc9)
- Refactor pagination filters (702ab74)
- Add validation handling (7e98eda)
- Fix feed error when articles without tags (8f616ae)
- Fix article tags list error (c9c3062)
- Add article feed v2 methods (16b52d5)
- Update article repo methods in article service (e539f6e)
- Add command to check tests typing (db07516)
- Fix tests missing typing annotations (7065eb5)
- Refactor other namings (0b65252)
- Refactor article & comment namings (4dd0760)
- Rename profile follow & unfollow service methods (243665e)
- Refactor profile service logic using user service instead of user repository (4d2eead)
- Move passwords logic to service (b681362)
- Refactor user and auth services (5bdb23f)
- Rename jwt token service (fc92776)
- Add logic to keep unique article slug id (2cd38f8)
- Update project requirements versions (8efaf4d)
- Update correct imports (a1fe5b5)
- Add util to handle get or create logic (bf49bfd)
- Remove migrations from tests coverage (50d4c4b)
- Rename requirement (pycharm can't find it) (ca5dca7)
- Disable some loggers (c47d815)
- Update documentation (38d8e1f)
- Update default migration (b8f247e)
- Update docker files & commands (8dc167e)
- Add default migration (b8b857c)
- Update README.md file (73772b3)
- Remove debug print (1cf71e7)
- Move user get and update logic from auth service to separated user service (39864eb)
- Add some tests for article endpoints (d609d4f)
- Handle error with empty article tags (e620d84)
- Add tests for tags endpoint (e5f266c)
- Add tests for profile endpoints (351b03b)
- Add test for health-check endpoint (2eef82c)
- Handle exceptions in profile follow logic (27e9f5a)
- Update user & auth tests (e30ea14)

