# PoC Development Prompts

This file contains ~40 powerful prompts for developing Proof-of-Concepts (PoCs) in bug bounty hunts. These prompts incorporate content from all your existing .txt files, focusing on creating triage-valid PoCs with tools like DevTools, Burp Suite, and AI, while emphasizing ethical impact demonstration.

From Master-prompt.txt:
- RECONNAISSANCE HUNTING: Activate as my elite vulnerability research partner - a P1 warrior specializing in browser-based security testing using advanced Developer Tools techniques and VS-Code powered analysis. Together we systematically hunt critical vulnerabilities through DOM manipulation, network traffic analysis, local/session storage inspection, console debugging, source code reverse engineering, and real-time payload injection. Focus on crafting valid POCs for XSS, CSRF, IDOR, authentication bypasses, business logic flaws, and client-side vulnerabilities. Leverage VS-Code for advanced JavaScript analysis, regex-based vulnerability pattern searching, source mapping, and POC development while using browser DevTools for real-time exploitation testing, cookie manipulation, header modification, and dynamic attack vector identification.

- JAVASCRIPT RECON ANALYSIS: Execute comprehensive security analysis of JavaScript files from target URLs using advanced static and dynamic analysis techniques. Systematically scan all client-side JavaScript (including Webpack bundles, minified code, source maps, and dynamic imports) to identify critical vulnerabilities including XSS injection points, insecure API endpoints, authentication bypass logic, CSRF token manipulation, DOM-based vulnerabilities, client-side storage weaknesses, and business logic flaws. Use advanced pattern matching, AST parsing, dependency analysis, and code flow tracing to extract sensitive information, hardcoded credentials, exposed API keys, and insecure configurations. Provide detailed vulnerability mapping, exploit POCs, and remediation strategies for all discovered security weaknesses in live JavaScript applications.

- Execute advanced information disclosure hunting through comprehensive browser console analysis, error message exploitation, and verbose logging reconnaissance. Systematically identify P1-level information disclosure vulnerabilities including stack trace exposure, sensitive error messages, debugging endpoints, verbose API responses, console.log data leakage, source map exposure, environment variable disclosure, internal IP addresses, database connection strings, and authentication token leaks. Use advanced console monitoring techniques, custom error injection payloads, verbose logging bypass methods, and client-side debugging artifact analysis to uncover critical information that could lead to system compromise, user data exposure, or privilege escalation.

From other files: Integrated content on PoC creation, video recording, reproducibility, and ethical testing.
# PoC Development Prompts

This file contains ~40 powerful prompts for developing Proof-of-Concepts (PoCs) in bug bounty hunts. These prompts incorporate content from all your existing .txt files, focusing on creating triage-valid PoCs with tools like DevTools, Burp Suite, and AI, while emphasizing ethical impact demonstration.

1. How can I create a PoC for XSS by recording a video of payload injection and alert execution in DevTools’ Console?

2. What steps can I take to develop a PoC for IDOR by demonstrating unauthorized data access in Burp Suite’s Repeater?

3. How can I craft a PoC for prototype pollution by showing state manipulation in DevTools’ Console?

4. What techniques can I use to build a PoC for SQLi by capturing error messages or data extraction in Burp Intruder?

5. How can I develop a PoC for auth bypass by manipulating variables in DevTools’ Sources tab and showing privilege escalation?

6. What AI tools can I use to generate PoC scripts for automating vulnerability demonstrations?

7. How can I create a PoC for SSRF by intercepting requests in Burp Suite and showing internal resource access?

8. What payloads can I use in a PoC for DOM-based XSS to prove session theft via cookie exfiltration?

9. How can I develop a PoC for business logic flaws by altering application state in DevTools and recording the impact?

10. What steps can I take to build a PoC for data leaks by extracting sensitive information from API responses?

11. How can I use Burp Suite’s Comparer to create a PoC showing response differences for access control issues?

12. What techniques can I apply to craft a PoC for CSRF by demonstrating unauthorized actions via crafted requests?

13. How can I develop a PoC for race conditions by timing API calls in DevTools’ Network tab?

14. What AI prompts can I use to optimize PoC development for maximum impact demonstration?

15. How can I create a PoC for open redirects by constructing malicious URLs and showing redirection?

16. What steps can I take to build a PoC for WebSocket vulnerabilities using Burp Suite’s interception?

17. How can I develop a PoC for file upload bypasses by uploading malicious files and triggering execution?

18. What payloads can I inject for a PoC of eval-based RCE in JavaScript?

19. How can I use DevTools’ Sources tab to create a PoC for asynchronous JavaScript exploitation?

20. What techniques can I use to demonstrate mass assignment in a PoC via Burp Repeater?

21. How can I craft a PoC for CORS misconfigurations by showing cross-origin data access?

22. What AI analysis can I perform to enhance PoC clarity and reproducibility?

23. How can I develop a PoC for rate limiting bypasses by directly calling APIs?

24. What steps can I take to build a PoC for debugging endpoint exposure?

25. How can I create a PoC for weak cryptography by decrypting or forging data?

26. What techniques can I apply to demonstrate header injections in a PoC?

27. How can I use symbolic execution to validate PoC for obfuscated vulnerabilities?

28. What payloads can I use for a PoC of postMessage-based data exfiltration?

29. How can I develop a PoC for multi-step workflow bypasses?

30. What AI-driven scripts can I create for automated PoC generation?

31. How can I record a PoC video showing real-world impact like account takeover?

32. What steps can I take to ensure PoC reproducibility for triage validation?

33. How can I combine tools (DevTools + Burp) for comprehensive PoC development?

34. What ethical considerations should I include in PoC demonstrations?

35. How can I use AI to generate PoC code snippets for complex exploits?

36. What techniques can I use to minimize PoC impact while proving severity?

37. How can I develop PoCs for chained vulnerabilities like XSS + IDOR?

38. What AI prompts can I use to refine PoC for better report acceptance?

39. How can I test PoC across different browsers for consistency?

40. What comprehensive PoC workflow can I follow from vulnerability confirmation to report submission?

# Additional 40 Prompts for Parameters, User-Functionality, Debugging, Injection Points, Manual Testing Scope, Static/Dynamic Testing

41. How can I develop a PoC for parameter injection points in JavaScript using static analysis?

42. What techniques create PoCs for user functionality parameters in JavaScript?

43. How can I debug and develop PoCs for JavaScript parameters with reflected injection?

44. What static testing PoCs demonstrate parameter vulnerabilities in JavaScript?

45. How can I use VS Code debugging to develop PoCs for parameter flow in JavaScript?

46. What manual testing scope includes PoCs for JavaScript parameters handling sensitive data?

47. How can I develop PoCs for injection points in JavaScript parameters using Burp Suite?

48. What user functionality mappings support PoC development for parameter flaws?

49. How can I debug parameter handling in JavaScript for PoC creation in DevTools?

50. What techniques develop PoCs for reflected parameters in JavaScript XSS?

51. How can I scope manual testing to include PoCs for JavaScript parameter validation?

52. What static analysis tools in VS Code help develop parameter injection PoCs?

53. How can I dynamically develop PoCs for JavaScript parameters in user functionality?

54. What debugging workflows in DevTools support parameter-based PoC creation?

55. How can I map user functionality parameters for targeted PoC development?

56. What static testing patterns create PoCs for dangerous parameters in JavaScript?

57. How can I use Burp Suite to develop PoCs for parameter vulnerabilities from JavaScript?

58. What user functionality debugging aids PoC development for parameter weaknesses?

59. How can I develop PoCs for reflected injection points in JavaScript parameters?

60. What manual testing scope develops PoCs for parameter security in JavaScript?

61. How can I debug JavaScript parameters for static PoC analysis?

62. What techniques map user functionality parameters for dynamic PoC testing?

63. How can I develop PoCs for parameter injection points using Console debugging?

64. What static testing methods create PoCs for JavaScript parameter validation?

65. How can I scope manual testing for parameter-based PoC development in JavaScript?

66. What debugging tools in DevTools help create parameter vulnerability PoCs?

67. How can I develop PoCs for reflected parameters in JavaScript through static analysis?

68. What user functionality mappings include parameter injection PoCs?

69. How can I use VS Code for debugging JavaScript parameters in PoC scenarios?

70. What techniques develop PoCs for injection points in JavaScript parameters with Burp?

71. How can I map user functionality parameters for PoC development?

72. What debugging workflows support parameter security PoC creation?

73. How can I develop PoCs for reflected injection points in JavaScript parameters?

74. What manual testing scope creates PoCs for parameter validation in user functionality?

75. How can I debug JavaScript parameters for dynamic PoC analysis?

76. What static testing patterns develop PoCs for dangerous parameters in JavaScript?

77. How can I use Console commands to create parameter injection PoCs?

78. What user functionality debugging includes parameter flow PoC tracing?

79. How can I scope manual testing for JavaScript parameter PoC development?

80. What comprehensive debugging approach combines static and dynamic testing for JavaScript parameters and user functionality PoC development?