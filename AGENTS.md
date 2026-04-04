# AGENTS.md

## Commit Message Convention

- Follow Conventional Commits for normal changes.
- Prefer `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, and `test:`.
- Use a scope when it adds clarity, for example `feat(docker): ...`.
- Match the existing repo style shown in recent history before inventing a new format.

## Repo Notes

- The main container definition lives in `Dockerfile.openclaw` and `docker-compose.yml`.
- Keep browser/runtime docs in `README.md` aligned with Docker changes.
- Do not include unrelated local files such as ad hoc `package-lock.json` files unless the repo explicitly starts tracking them.
