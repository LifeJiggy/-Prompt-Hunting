# Chaining Prompts

This file contains ~40 powerful prompts for chaining vulnerabilities in bug bounty hunts. These prompts integrate content from all your existing .txt files, focusing on combining flaws like XSS + IDOR for maximum impact, with ethical tool use.

From Master-prompt.txt:
- RECONNAISSANCE HUNTING: Activate as my elite vulnerability research partner - a P1 warrior specializing in browser-based security testing using advanced Developer Tools techniques and VS-Code powered analysis. Together we systematically hunt critical vulnerabilities through DOM manipulation, network traffic analysis, local/session storage inspection, console debugging, source code reverse engineering, and real-time payload injection. Focus on crafting valid POCs for XSS, CSRF, IDOR, authentication bypasses, business logic flaws, and client-side vulnerabilities. Leverage VS-Code for advanced JavaScript analysis, regex-based vulnerability pattern searching, source mapping, and POC development while using browser DevTools for real-time exploitation testing, cookie manipulation, header modification, and dynamic attack vector identification.

- JAVASCRIPT RECON ANALYSIS: Execute comprehensive security analysis of JavaScript files from target URLs using advanced static and dynamic analysis techniques. Systematically scan all client-side JavaScript (including Webpack bundles, minified code, source maps, and dynamic imports) to identify critical vulnerabilities including XSS injection points, insecure API endpoints, authentication bypass logic, CSRF token manipulation, DOM-based vulnerabilities, client-side storage weaknesses, and business logic flaws. Use advanced pattern matching, AST parsing, dependency analysis, and code flow tracing to extract sensitive information, hardcoded credentials, exposed API keys, and insecure configurations. Provide detailed vulnerability mapping, exploit POCs, and remediation strategies for all discovered security weaknesses in live JavaScript applications.

- Execute advanced information disclosure hunting through comprehensive browser console analysis, error message exploitation, and verbose logging reconnaissance. Systematically identify P1-level information disclosure vulnerabilities including stack trace exposure, sensitive error messages, debugging endpoints, verbose API responses, console.log data leakage, source map exposure, environment variable disclosure, internal IP addresses, database connection strings, and authentication token leaks. Use advanced console monitoring techniques, custom error injection payloads, verbose logging bypass methods, and client-side debugging artifact analysis to uncover critical information that could lead to system compromise, user data exposure, or privilege escalation.

From other files: Integrated content on chaining techniques, multi-step exploits, and impact escalation.
# Chaining Prompts

This file contains ~40 powerful prompts for chaining vulnerabilities in bug bounty hunts. These prompts integrate content from all your existing .txt files, focusing on combining flaws like XSS + IDOR for maximum impact, with ethical tool use.

1. How can I chain XSS with IDOR by using XSS to steal session tokens and access unauthorized API endpoints?

2. What techniques can I use to combine prototype pollution with auth bypass in JavaScript for privilege escalation?

3. How can I chain CSRF with data leaks by exploiting CSRF to trigger API calls that expose sensitive information?

4. What steps can I take to link SSRF with RCE by using SSRF to access internal services vulnerable to command injection?

5. How can I exploit a chain of DOM-based XSS and business logic flaws to manipulate application state?

6. What AI analysis can I perform to identify potential vulnerability chains in JavaScript and APIs?

7. How can I chain open redirects with phishing by crafting URLs that lead to malicious sites?

8. What techniques can I use to combine race conditions with IDOR for unauthorized data access?

9. How can I chain WebSocket vulnerabilities with XSS for real-time data exfiltration?

10. What payloads can I craft to chain eval injection with prototype pollution in JavaScript?

11. How can I use Burp Suite to chain header injections with SSRF for internal resource access?

12. What steps can I take to combine CORS misconfigurations with postMessage for cross-origin attacks?

13. How can I chain file upload bypasses with RCE by uploading malicious files to vulnerable endpoints?

14. What AI prompts can I use to generate chaining strategies for multiple JavaScript flaws?

15. How can I exploit a chain of client-side validation bypasses and server-side SQLi?

16. What techniques can I apply to chain mass assignment with privilege escalation in APIs?

17. How can I combine verbose error messages with SSRF to leak internal system details?

18. What steps can I take to chain authentication token leaks with session hijacking?

19. How can I use DevTools to chain DOM clobbering with XSS for enhanced exploitation?

20. What payloads can I inject to chain command injection with SSRF in JavaScript?

21. How can I chain insecure API configurations with IDOR for broader data exposure?

22. What AI-driven heatmaps can I create to visualize and prioritize vulnerability chains?

23. How can I combine rate limiting bypasses with brute-force attacks on APIs?

24. What techniques can I use to chain debugging endpoints with information disclosure?

25. How can I exploit a chain of weak cryptography and data leaks in JavaScript?

26. What steps can I take to combine multi-step workflow bypasses with business logic flaws?

27. How can I chain header-based injections with open redirects for phishing?

28. What AI analysis can I perform to predict the impact of chaining specific vulnerabilities?

29. How can I use Burp Suite’s Comparer to identify chains involving subtle response differences?

30. What techniques can I apply to chain asynchronous JavaScript flaws with race conditions?

31. How can I combine client-side storage weaknesses with XSS for session theft?

32. What payloads can I craft for chaining prototype pollution with DOM manipulation?

33. How can I chain CORS with CSRF for cross-origin request forgery?

34. What steps can I take to combine blind vulnerabilities with error-based disclosures?

35. How can I use symbolic execution to identify complex chaining opportunities in JavaScript?

36. What AI prompts can I use to simulate and validate vulnerability chains?

37. How can I chain insecure direct object references with horizontal privilege escalation?

38. What techniques can I apply to combine injection flaws with data exfiltration?

39. How can I exploit a chain of obfuscated JavaScript vulnerabilities for maximum impact?

40. What comprehensive chaining workflow can I follow to escalate low-severity bugs to P1 exploits?

# Additional 40 Prompts for Parameters, User-Functionality, Debugging, Injection Points, Manual Testing Scope, Static/Dynamic Testing

41. How can I chain parameter injection points in JavaScript with other vulnerabilities for maximum impact?

42. What techniques chain user functionality parameters in JavaScript with auth bypasses?

43. How can I debug and chain JavaScript parameters for reflected injection with SSRF?

44. What static testing chains parameter vulnerabilities in JavaScript with data leaks?

45. How can I use VS Code debugging to chain parameter flow in JavaScript with IDOR?

46. What manual testing scope chains JavaScript parameters with business logic flaws?

47. How can I chain injection points in JavaScript parameters using Burp Suite for exploitation?

48. What user functionality mappings chain parameter-based flaws with XSS?

49. How can I debug parameter handling in JavaScript for chaining with prototype pollution?

50. What techniques chain reflected parameters in JavaScript with CSRF?

51. How can I scope manual testing to chain JavaScript parameter validation with RCE?

52. What static analysis tools in VS Code chain parameter injection risks with API flaws?

53. How can I dynamically chain JavaScript parameters for user functionality bypasses?

54. What debugging workflows in DevTools chain parameter-based vulnerabilities with race conditions?

55. How can I map user functionality parameters for targeted chaining?

56. What static testing patterns chain dangerous parameters in JavaScript with SQLi?

57. How can I use Burp Suite to chain parameter vulnerabilities from JavaScript with SSRF?

58. What user functionality debugging chains parameter weaknesses with auth bypass?

59. How can I chain reflected injection points in JavaScript parameters with data exfiltration?

60. What manual testing scope chains parameter security in JavaScript with privilege escalation?

61. How can I debug JavaScript parameters for static chaining analysis?

62. What techniques map user functionality parameters for dynamic chaining?

63. How can I chain parameter injection points using Console debugging with WebSocket flaws?

64. What static testing methods chain JavaScript parameters with insecure deserialization?

65. How can I scope manual testing for parameter-based chaining in JavaScript?

66. What debugging tools in DevTools help chain parameter vulnerabilities with XXE?

67. How can I chain reflected parameters in JavaScript through static analysis with CORS?

68. What user functionality mappings chain parameter injection risks with JWT flaws?

69. How can I use VS Code for debugging JavaScript parameters in chaining scenarios?

70. What techniques chain injection points in JavaScript parameters with Burp for LDAP injection?

71. How can I map user functionality parameters for vulnerability chaining?

72. What debugging workflows chain parameter security issues with command injection?

73. How can I chain reflected injection points in JavaScript parameters with open redirects?

74. What manual testing scope chains parameter validation in user functionality with SSTI?

75. How can I debug JavaScript parameters for dynamic chaining analysis?

76. What static testing patterns chain dangerous parameters in JavaScript with file inclusion?

77. How can I use Console commands to chain parameter injection points with header injection?

78. What user functionality debugging chains parameter flow tracing with mass assignment?

79. How can I scope manual testing for JavaScript parameter chaining?

80. What comprehensive debugging approach combines static and dynamic testing for JavaScript parameters and user functionality chaining?