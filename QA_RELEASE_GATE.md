# Project Zero-Bug Release Gate

Evidence-based release checklist. UNKNOWN is never PASS.

- [ ] Requirements/device/browser/auth/API/data/integration/security/accessibility defined
- [ ] Architecture/dependencies/env/secrets reviewed
- [ ] Static audit for debug/TODO/FIXME/HACK, secrets/private keys, unsafe HTML/eval/URLs, unsafe casts, unhandled promises, races, dead code, fake success
- [ ] Install/typecheck/lint/build/routes PASS; warnings classified
- [ ] Functional failure paths, API/data/auth/security/accessibility/responsive/performance/network checks complete
- [ ] Production deployment/smoke/telemetry reviewed
- [ ] Adversarial QA and regression tests complete

## Final gate
Critical bugs = 0; high-severity known bugs = 0; critical paths verified; no critical UNKNOWN items.

**Build/deployment success alone never means bug-free.**