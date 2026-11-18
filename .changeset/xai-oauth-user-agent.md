---
'e2e': patch
---

`e2e login spacexai` and the SuperGrok token refresh now send `User-Agent: e2e/<version> (<platform>; <arch>)` to SpaceXAI's sign-in server, as model requests already do. They used to send the runtime's default, `node`.
