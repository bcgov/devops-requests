---
name: Request for selective recovery of Vault secrets
about: To recover individual Vault secrets from a backup, as opposed to a full system restore
title: ''
labels: ''
assignees: ShellyXueHan, caggles, IanKWatts, w8896699
---

## Recover secrets from Vault
**Emergencies Only**

In the case of an emergency, it is possible to recover individual secrets from a Vault backup.  

Did you know that **Vault secrets are version controlled**?  Updates to Vault secrets involve the creation of a new version.  Vault keeps up to ten versions, so if a secret has merely been changed, you can access the previous values by viewing the older version of the secret.

You must already have access to Vault.  Authentication to the temporary instance is the same as for the production instance.

### Checklist:
* Are you sure that the values you need are not available in a previous version of the secret?
* Is there no other way to recover the secret?
* Is this an emergency?
* Did the change happen less than a week ago?
* Do you have access to the Vault role in question?

### Request recovery
If you answered 'yes' to all of the questions in the checklist, then please provide the following information:

* Date: The date and time to restore from
* Project ID (License Plate): e.g. abc123
* Explanation: Tell us what happened and why you think you need this


