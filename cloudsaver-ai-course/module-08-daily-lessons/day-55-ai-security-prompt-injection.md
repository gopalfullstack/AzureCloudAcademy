# Day 55 – AI Security and Prompt Injection Testing

**Module:** 08 – Security, Testing, Integration and Final Product Development  
**Programme day:** 55  
**Duration:** 3.5 hours

## Learning objective

Test whether untrusted prompts and retrieved content can bypass CloudSaver's safeguards.

## Detailed topics

1. Prompt injection
2. indirect injection in retrieved documents
3. data exfiltration
4. scope escape
5. tool allow-lists
6. least privilege
7. output validation
8. grounding
9. refusal
10. content filtering
11. logging
12. red-team scenarios
13. human oversight.

## Where to learn

- [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [Azure AI Content Safety](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/overview)
- [Prompt Shields](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/jailbreak-detection)

## Hands-on practical lab

Create malicious and benign test prompts, including instructions embedded in retrieved documents and requests for another subscription's data. Verify the agent treats retrieved text as untrusted and cannot invoke unapproved tools.

## Expected deliverables

- [ ] Prompt injection test suite
- [ ] expected/actual results
- [ ] mitigation notes
- [ ] regression cases.

## Completion checklist

- [ ] Out-of-scope data is not returned
- [ ] retrieved instructions cannot override system policy
- [ ] tool permissions remain restricted
- [ ] failures are logged.

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
