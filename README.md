# firewall-policy-audit
An automated Firewall policy audit tool - just upload the csv or excel file of the firewall
FastAPI app with upload → audit → download flow

Excel generator with:

Color-coded findings

Per-category sheets (Redundant/Disabled, Overly Permissive, Unused/Stale, No Security Profiles, Temp/Test, Shadow/Overlapping, Legacy, Logging Gaps)

Shadow/overlap heuristic

Top high-risk sheet & hygiene checks

Optional login (username/password)

Azure SAML scaffold (routes stubbed; safe to enable later)

Dockerfile set to EXPOSE 4343
