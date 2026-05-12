# ShadowGate Incident Investigation Draft

## Summary

During a simulated threat hunting exercise, analysts identified references to legacy infrastructure potentially exposed through historical indexing services.

---

## Analyst Notes

- Archived endpoints were still visible through cached search engine snapshots.
- Historical mirrors may still respond through alternative routing networks.
- Several usernames were reused across external platforms.

---

## Possible Legacy Endpoints

```txt
/internal/archive/
/admin-shadow/
/onion/
```

---

## Internal Observation

The investigation team identified that some media files still contain metadata references that may reveal additional information.

Analysts should review:
- image metadata
- historical snapshots
- hidden comments
- encoded references

---

## Historical Reference

Mirror node reference:

```txt
c2hhZG93Z2F0ZS1taXJyb3Iub25pb24=
```

---

## Analyst Reminder

Some answers are not visible to the naked eye.

---

### Training Flag

RSC{incident_draft_discovered}

<!-- RSC{github_hidden_comment_flag} -->
