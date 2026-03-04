# OctoAcme — Release Readiness Checklist

Use this checklist during the Release Readiness Review to confirm all pre-release criteria are met before deploying to production. The Release Manager owns this checklist; all listed roles contribute sign-off in their area.

**Ref:** [Release & Deployment](../octoacme-release-and-deployment.md), [Roles & Ceremonies](../octoacme-roles-and-ceremonies.md)

---

## Release Metadata

- **Release name / version:**
- **Target deployment date:**
- **Release Manager:**
- **QA Lead:**
- **Technical Lead:**
- **PM / PdM:**

---

## Ownership & Approvals

| Sign-off Area | Owner | Status | Notes |
|---|---|---|---|
| Release scheduling and coordination | Release Manager | ☐ Approved | |
| Test completion and quality sign-off | QA Lead | ☐ Approved | |
| Technical architecture and deployment approach | Technical Lead | ☐ Approved | |
| Scope, acceptance criteria, and stakeholder alignment | PM / PdM | ☐ Approved | |

---

## Acceptance Criteria & Scope

- [ ] All planned features and fixes are merged and in staging
- [ ] All acceptance criteria reviewed and confirmed met
- [ ] Any scope changes are documented and approved by PM / PdM
- [ ] Release notes drafted and reviewed

---

## Test Status

- [ ] Unit and integration tests pass in CI
- [ ] End-to-end / smoke tests pass in staging
- [ ] Security scanning completed with no blocking findings
- [ ] Performance / load testing completed (if applicable)
- [ ] Manual QA completed for critical user flows
- [ ] All P0/P1 defects resolved or explicitly deferred with owner and timeline
- [ ] QA Lead sign-off recorded

---

## Rollout Plan

- [ ] Deployment window confirmed and communicated
- [ ] Phased rollout or feature flag strategy documented (if applicable)
- [ ] Deployment runbook reviewed by Technical Lead and Release Manager
- [ ] On-call or support team notified of release window

---

## Communications Plan

- [ ] Internal stakeholder notification drafted and scheduled
- [ ] Customer-facing communications prepared (if applicable)
- [ ] Support team briefed on new features, known issues, and escalation path
- [ ] Release notes published or queued for publication

---

## Rollback Plan

- [ ] Rollback steps documented and tested
- [ ] Rollback owner identified (Technical Lead or Release Manager)
- [ ] Rollback trigger criteria defined (e.g., error rate threshold, critical defect)
- [ ] Previous known-good release or artifact available

---

## Monitoring & Observability

- [ ] Key metrics and alerts configured for the new release
- [ ] Dashboards reviewed and updated if new signals are added
- [ ] On-call rotation and escalation path confirmed for post-release window
- [ ] Post-release verification steps scheduled (see [Release & Deployment](../octoacme-release-and-deployment.md))

---

## Final Go / No-Go Decision

| Role | Decision | Date |
|---|---|---|
| Release Manager | ☐ Go / ☐ No-Go | |
| QA Lead | ☐ Go / ☐ No-Go | |
| Technical Lead | ☐ Go / ☐ No-Go | |
| PM / PdM | ☐ Go / ☐ No-Go | |

**Notes / Conditions:**
*(Document any conditions for go-ahead, partial rollout decisions, or deferred items here)*

