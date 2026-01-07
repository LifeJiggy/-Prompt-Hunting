# Reporting Prompts

This file contains ~40 powerful prompts for reporting vulnerabilities in bug bounty hunts. These prompts synthesize content from all your existing .txt files, focusing on creating triage-valid reports with strong PoCs, impact analysis, and ethical guidelines.

From Master-prompt.txt:
- RECONNAISSANCE HUNTING: Activate as my elite vulnerability research partner - a P1 warrior specializing in browser-based security testing using advanced Developer Tools techniques and VS-Code powered analysis. Together we systematically hunt critical vulnerabilities through DOM manipulation, network traffic analysis, local/session storage inspection, console debugging, source code reverse engineering, and real-time payload injection. Focus on crafting valid POCs for XSS, CSRF, IDOR, authentication bypasses, business logic flaws, and client-side vulnerabilities. Leverage VS-Code for advanced JavaScript analysis, regex-based vulnerability pattern searching, source mapping, and POC development while using browser DevTools for real-time exploitation testing, cookie manipulation, header modification, and dynamic attack vector identification.

- JAVASCRIPT RECON ANALYSIS: Execute comprehensive security analysis of JavaScript files from target URLs using advanced static and dynamic analysis techniques. Systematically scan all client-side JavaScript (including Webpack bundles, minified code, source maps, and dynamic imports) to identify critical vulnerabilities including XSS injection points, insecure API endpoints, authentication bypass logic, CSRF token manipulation, DOM-based vulnerabilities, client-side storage weaknesses, and business logic flaws. Use advanced pattern matching, AST parsing, dependency analysis, and code flow tracing to extract sensitive information, hardcoded credentials, exposed API keys, and insecure configurations. Provide detailed vulnerability mapping, exploit POCs, and remediation strategies for all discovered security weaknesses in live JavaScript applications.

- Execute advanced information disclosure hunting through comprehensive browser console analysis, error message exploitation, and verbose logging reconnaissance. Systematically identify P1-level information disclosure vulnerabilities including stack trace exposure, sensitive error messages, debugging endpoints, verbose API responses, console.log data leakage, source map exposure, environment variable disclosure, internal IP addresses, database connection strings, and authentication token leaks. Use advanced console monitoring techniques, custom error injection payloads, verbose logging bypass methods, and client-side debugging artifact analysis to uncover critical information that could lead to system compromise, user data exposure, or privilege escalation.

From other files: Integrated content on report structure, PoC inclusion, impact quantification, and ethical disclosure.
# Reporting Prompts

This file contains ~40 powerful prompts for reporting vulnerabilities in bug bounty hunts. These prompts synthesize content from all your existing .txt files, focusing on creating triage-valid reports with strong PoCs, impact analysis, and ethical guidelines.

1. How can I structure a bug bounty report for XSS to include title, description, steps, impact, PoC, and mitigation?

2. What elements should I include in a report for IDOR to prove unauthorized data access and avoid duplicates?

3. How can I write a report for prototype pollution that demonstrates state manipulation and real-world impact?

4. What steps can I take to ensure a SQLi report is accepted by including error messages and data extraction PoCs?

5. How can I craft a report for auth bypass that shows privilege escalation with clear reproduction steps?

6. What AI tools can I use to draft and refine bug bounty reports for better clarity?

7. How can I report SSRF with evidence of internal resource access and potential RCE chaining?

8. What techniques can I use to make a DOM-based XSS report unique and high-impact?

9. How can I develop a report for business logic flaws with quantifiable financial or data impact?

10. What should I include in a data leak report to highlight PII exposure and compliance risks?

11. How can I use Burp Suite logs in reports to support access control vulnerability claims?

12. What payloads and screenshots should I add to a CSRF report for reproducibility?

13. How can I report race conditions with timing evidence and impact on multi-user systems?

14. What AI prompts can I use to generate impact statements for vulnerability reports?

15. How can I structure a report for open redirects to show phishing potential?

16. What steps can I take to report WebSocket vulnerabilities with message interception evidence?

17. How can I craft a report for file upload bypasses including execution PoCs?

18. What mitigation suggestions should I include in an RCE report?

19. How can I report asynchronous JavaScript flaws with debugging traces?

20. What elements make a mass assignment report triage-ready?

21. How can I demonstrate CORS misconfiguration impact in a report?

22. What AI analysis can I add to reports for vulnerability prioritization?

23. How can I report rate limiting bypasses with brute-force evidence?

24. What should I include in a debugging endpoint exposure report?

25. How can I report weak cryptography with decryption PoCs?

26. What techniques can I use to avoid 'informative' rejections in header injection reports?

27. How can I use symbolic execution outputs in reports for obfuscated vulnerabilities?

28. What payloads should I document in postMessage vulnerability reports?

29. How can I report multi-step workflow bypasses with step-by-step evidence?

30. What AI-driven scripts can I use to automate report formatting?

31. How can I record and embed PoC videos in reports for maximum impact?

32. What ethical reminders should I include in all reports?

33. How can I combine tools' outputs (DevTools, Burp) in report evidence?

34. What makes a report unique to avoid duplicate rejections?

35. How can I quantify impact in reports for higher bounty payouts?

36. What AI prompts can I use to improve report language and professionalism?

37. How can I report chained vulnerabilities like XSS + IDOR with combined PoCs?

38. What follow-up information should I provide if a report is questioned?

39. How can I test report reproducibility before submission?

40. What comprehensive reporting workflow can I follow from PoC to submission and follow-up?

# Additional 40 Prompts for Parameters, User-Functionality, Debugging, Injection Points, Manual Testing Scope, Static/Dynamic Testing

41. How can I report parameter injection points in JavaScript with detailed PoCs?

42. What techniques report user functionality parameters in JavaScript vulnerabilities?

43. How can I debug and report JavaScript parameters with reflected injection evidence?

44. What static testing reports demonstrate parameter vulnerabilities in JavaScript?

45. How can I use VS Code debugging to report parameter flow in JavaScript issues?

46. What manual testing scope should I report for JavaScript parameters handling sensitive data?

47. How can I report injection points in JavaScript parameters using Burp Suite logs?

48. What user functionality mappings support reporting parameter-based flaws?

49. How can I debug parameter handling in JavaScript for inclusion in reports?

50. What techniques report reflected parameters in JavaScript XSS findings?

51. How can I scope manual testing reports for JavaScript parameter validation?

52. What static analysis tools in VS Code help report parameter injection risks?

53. How can I dynamically report JavaScript parameters for user functionality issues?

54. What debugging workflows in DevTools support parameter-based report evidence?

55. How can I map user functionality parameters for targeted reporting?

56. What static testing patterns create reports for dangerous parameters in JavaScript?

57. How can I use Burp Suite to report parameter vulnerabilities from JavaScript analysis?

58. What user functionality debugging aids reporting parameter weaknesses?

59. How can I report reflected injection points in JavaScript parameters?

60. What manual testing scope reports parameter security in JavaScript?

61. How can I debug JavaScript parameters for static report analysis?

62. What techniques map user functionality parameters for dynamic reporting?

63. How can I report parameter injection points using Console debugging evidence?

64. What static testing methods validate JavaScript parameters for reports?

65. How can I scope manual testing for parameter-based reporting in JavaScript?

66. What debugging tools in DevTools help create parameter vulnerability reports?

67. How can I report reflected parameters in JavaScript through static analysis?

68. What user functionality mappings include parameter injection reports?

69. How can I use VS Code for debugging JavaScript parameters in reporting?

70. What techniques report injection points in JavaScript parameters with Burp evidence?

71. How can I map user functionality parameters for vulnerability reporting?

72. What debugging workflows support parameter security report creation?

73. How can I report reflected injection points in JavaScript parameters?

74. What manual testing scope creates reports for parameter validation in user functionality?

75. How can I debug JavaScript parameters for dynamic report analysis?

76. What static testing patterns report dangerous parameters in JavaScript?

77. How can I use Console commands to document parameter injection points in reports?

78. What user functionality debugging includes parameter flow report tracing?

79. How can I scope manual testing for JavaScript parameter reporting?

80. What comprehensive debugging approach combines static and dynamic testing for JavaScript parameters and user functionality reporting?