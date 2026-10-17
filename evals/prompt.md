# Routing Evaluation Cases

Route each input to the single best skill using its description and trigger phrases.
Do not count a test as passing merely because the response mentions the expected skill.

| ID | User input | Expected route |
|---|---|---|
| E2E-EN-01 | e2e it | e2e-session |
| E2E-EN-02 | start testing | e2e-session |
| E2E-HI-01 | ई2ई चलाओ | e2e-session |
| E2E-HI-02 | इसका टेस्ट करो | e2e-session |
| E2E-ROM-01 | e2e chalao | e2e-session |
| E2E-ROM-02 | iska test karo | e2e-session |
| BUG-EN-01 | report it | quick-bug |
| BUG-HI-01 | बग रिपोर्ट करो | quick-bug |
| BUG-HI-02 | इश्यू दर्ज करो | quick-bug |
| BUG-ROM-01 | bug report karo | quick-bug |
| BUG-ROM-02 | issue darj karo | quick-bug |
| TEST-EN-01 | write tests | write-tests |
| TEST-HI-01 | टेस्ट लिखो | write-tests |
| TEST-HI-02 | टेस्ट केस बनाओ | write-tests |
| TEST-ROM-01 | test likho | write-tests |
| TEST-ROM-02 | test cases banao | write-tests |
| NEG-01 | Explain what software testing means | NO_ROUTE |
| NEG-02 | What is the Hindi word for bug report? | NO_ROUTE |

## Execution
Run every case in a fresh routing decision. Record the actual route and pass/fail.
Do not modify the expected route after seeing the result.
