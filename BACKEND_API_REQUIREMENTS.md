# Meetz Backend API Requirements

## Change Requests

POST /change-requests
GET /change-requests
GET /change-requests/:id
POST /change-requests/:id/approve
POST /change-requests/:id/reject

---

## Execution

POST /execution/:id
GET /execution/:id/status

---

## Logs

GET /logs/:id
WS /logs/:id/stream

---

## AI

POST /ai/process
POST /ai/analyze-logs

---

## GitOps

POST /gitops/commit
POST /gitops/diff
POST /gitops/pr

---

## Incidents

POST /incidents
GET /incidents

---

## Auth (future)

POST /auth/login
POST /auth/register

---

## Organization (future)

GET /orgs
POST /orgs
