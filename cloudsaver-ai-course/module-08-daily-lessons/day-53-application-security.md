# Day 53 – Application Security and Least Privilege

**Module:** 08 – Security, Testing, Integration and Final Product Development  
**Programme day:** 53  
**Duration:** 3.5 hours

## Learning objective

Review the CloudSaver architecture and protect identities, data and APIs.

## Detailed topics

1. Secure architecture
2. Entra ID roles
3. least privilege
4. managed identities
5. Key Vault
6. API authN/authZ
7. input validation
8. SQL injection prevention
9. TLS
10. encryption at rest
11. sensitive data handling
12. audit logs
13. tenant/scope isolation
14. dependency/container security.

## Where to learn

- [Azure security baseline](https://learn.microsoft.com/en-us/security/benchmark/azure/overview)
- [Key Vault](https://learn.microsoft.com/en-us/azure/key-vault/general/overview)
- [OWASP API Security](https://owasp.org/www-project-api-security/)

## Hands-on practical lab

Perform a security review of the development environment. Search code/config for secrets, validate API role enforcement, review database permissions and verify a user cannot access another scope's data.

## Expected deliverables

- [ ] Security checklist
- [ ] permission matrix
- [ ] secret scan evidence
- [ ] remediation list.

## Completion checklist

- [ ] No hard-coded secrets
- [ ] sensitive endpoints enforce roles
- [ ] data scope is checked server-side
- [ ] audit events are recorded.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and review | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and validation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Product safety:** Use synthetic or explicitly authorised data. Keep production write actions disabled in the training MVP. Record limitations and require human approval for any future operational change.
