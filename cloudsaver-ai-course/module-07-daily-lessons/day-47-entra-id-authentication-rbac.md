# Day 47 – Microsoft Entra ID Authentication and RBAC

**Module:** 07 – FastAPI, Terraform, DevOps and Application Deployment  
**Programme day:** 47  
**Duration:** 3.5 hours

## Learning objective

Protect CloudSaver APIs and enforce user permissions on the server.

## Detailed topics

1. Authentication versus authorisation
2. OAuth 2.0/OIDC
3. Entra app registration
4. access tokens/JWT
5. issuer/audience/signature validation
6. scopes and app roles
7. RBAC
8. finance/engineer/approver/admin roles
9. endpoint permissions
10. subscription/tenant scope filtering
11. least privilege
12. token expiry.

## Where to learn

- [Microsoft identity platform](https://learn.microsoft.com/en-us/entra/identity-platform/v2-overview)
- [FastAPI security](https://fastapi.tiangolo.com/tutorial/security/)
- [App roles](https://learn.microsoft.com/en-us/entra/identity-platform/howto-add-app-roles-in-apps)

## Hands-on practical lab

Protect selected endpoints with a supported identity flow or instructor-provided test tokens. Implement role checks and test allowed/denied access for finance, engineer and approver personas. Enforce data scope in backend queries.

## Expected deliverables

- [ ] Auth configuration notes
- [ ] role/permission matrix
- [ ] protected endpoints
- [ ] positive and negative test results.

## Completion checklist

- [ ] Tokens are validated, not merely decoded
- [ ] permissions are checked server-side
- [ ] users cannot query out-of-scope subscriptions
- [ ] no secrets committed.

## Suggested session timetable

| Activity | Time |
|---|---:|
| Concepts and architecture | 45 min |
| Instructor demonstration | 45 min |
| Guided implementation | 60 min |
| Independent lab and validation | 45 min |
| Review and questions | 15 min |
| **Total** | **3.5 hours** |

**Deployment safety:** Use a dedicated development environment and budget. Apply least privilege, keep secrets in approved secret stores and review Terraform plans before provisioning resources.
