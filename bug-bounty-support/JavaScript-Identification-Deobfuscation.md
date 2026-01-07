# JavaScript Identification and Deobfuscation Prompts

This file contains ~40 powerful prompts for identifying backbone JavaScript files and deobfuscating them in bug bounty hunts. These prompts draw from all your existing .txt files, focusing on ethical, iterative analysis with tools like Burp Suite, DevTools, VS Code, and AI.

From Master-prompt.txt:
- RECONNAISSANCE HUNTING: Activate as my elite vulnerability research partner - a P1 warrior specializing in browser-based security testing using advanced Developer Tools techniques and VS-Code powered analysis. Together we systematically hunt critical vulnerabilities through DOM manipulation, network traffic analysis, local/session storage inspection, console debugging, source code reverse engineering, and real-time payload injection. Focus on crafting valid POCs for XSS, CSRF, IDOR, authentication bypasses, business logic flaws, and client-side vulnerabilities. Leverage VS-Code for advanced JavaScript analysis, regex-based vulnerability pattern searching, source mapping, and POC development while using browser DevTools for real-time exploitation testing, cookie manipulation, header modification, and dynamic attack vector identification.

- JAVASCRIPT RECON ANALYSIS: Execute comprehensive security analysis of JavaScript files from target URLs using advanced static and dynamic analysis techniques. Systematically scan all client-side JavaScript (including Webpack bundles, minified code, source maps, and dynamic imports) to identify critical vulnerabilities including XSS injection points, insecure API endpoints, authentication bypass logic, CSRF token manipulation, DOM-based vulnerabilities, client-side storage weaknesses, and business logic flaws. Use advanced pattern matching, AST parsing, dependency analysis, and code flow tracing to extract sensitive information, hardcoded credentials, exposed API keys, and insecure configurations. Provide detailed vulnerability mapping, exploit POCs, and remediation strategies for all discovered security weaknesses in live JavaScript applications.

- Execute advanced information disclosure hunting through comprehensive browser console analysis, error message exploitation, and verbose logging reconnaissance. Systematically identify P1-level information disclosure vulnerabilities including stack trace exposure, sensitive error messages, debugging endpoints, verbose API responses, console.log data leakage, source map exposure, environment variable disclosure, internal IP addresses, database connection strings, and authentication token leaks. Use advanced console monitoring techniques, custom error injection payloads, verbose logging bypass methods, and client-side debugging artifact analysis to uncover critical information that could lead to system compromise, user data exposure, or privilege escalation.

From other files: Integrated content on backbone JS identification, deobfuscation techniques, and ethical reverse engineering.
# JavaScript Identification and Deobfuscation Prompts

This file contains ~40 powerful prompts for identifying backbone JavaScript files and deobfuscating them in bug bounty hunts. These prompts draw from all your existing .txt files, focusing on ethical, iterative analysis with tools like Burp Suite, DevTools, VS Code, and AI.

1. How can I use Burp Suite’s sitemap and DevTools’ Network tab to enumerate all JavaScript files loaded by a target URL, prioritizing those likely to be the backbone (e.g., app.js, bundle.js) based on size and initiator?

2. What patterns in DevTools’ Network tab (e.g., file size >100KB, dynamic loading on user actions) indicate a JavaScript file is central to the application’s core functionality?

3. How can I use custom Regex patterns in VS Code (e.g., auth|app|main|api) to filter and identify backbone JavaScript files from Burp’s sitemap or Network exports?

4. What techniques can I use in DevTools’ Sources tab to trace which JavaScript file handles critical user interactions like login or API calls via breakpoints and call stacks?

5. How can I confirm a JavaScript file is the backbone by disabling it in DevTools’ Network tab and observing if core functionality (e.g., forms, navigation) breaks?

6. What Console commands (e.g., getEventListeners(document), monitorEvents) can I use to map event listeners to specific JavaScript files driving user functionality?

7. How can I use Burp Suite’s Proxy to intercept dynamic JavaScript loads and identify files triggered by user actions or API responses?

8. What indicators in JavaScript file names or paths (e.g., /static/js/, versioned bundles) suggest they are backbone files for core user functionality?

9. How can I use VS Code’s search with Regex (e.g., fetch|innerHTML|addEventListener) to analyze a suspected backbone JavaScript file for patterns indicating user interaction handling?

10. What AI techniques can I apply to summarize a JavaScript file’s purpose and identify if it’s the backbone based on functions like loginUser or handleSubmit?

11. How can I deobfuscate a minified JavaScript file using VS Code’s Prettier extension to understand its structure and identify backbone functionality?

12. What tools like JSDetox or de4js can I use to reverse-engineer obfuscated JavaScript and extract readable function names and logic?

13. How can I use DevTools’ Sources tab to set breakpoints on obfuscated functions and step through execution to reveal their purpose in user functionality?

14. What Regex patterns (e.g., eval|Function|encrypted strings) can I use in VS Code to detect obfuscation techniques in a backbone JavaScript file?

15. How can I apply symbolic execution or AI-driven analysis to deobfuscate complex JavaScript bundles and reconstruct original source architecture?

16. How can I use AST parsing (e.g., via Babel) to analyze and rename variables/functions in obfuscated JavaScript for better understanding of backbone logic?

17. What techniques can I use to handle Webpack bundle formats (IIFE, UMD, ESM) when deobfuscating JavaScript to identify module dependencies and core functionality?

18. How can I trace control flow in obfuscated JavaScript using DevTools’ debugger to uncover hidden user interaction handlers?

19. What AI prompts can I use to generate deobfuscation strategies for specific patterns like string encoding or control flow flattening in backbone JS?

20. How can I ethically reverse-engineer encrypted JavaScript without modifying the target, focusing on static analysis in VS Code?

21. What framework-specific patterns (e.g., React JSX, Angular decorators) should I look for when identifying and deobfuscating backbone JavaScript?

22. How can I use dependency graph analysis to map how a deobfuscated JavaScript file interacts with other modules in a large codebase?

23. What Console commands can I use to call deobfuscated functions directly and observe their impact on DOM or API calls?

24. How can I integrate AI with Regex to prioritize deobfuscation efforts on JavaScript files most likely containing vulnerable backbone logic?

25. What advanced techniques like runtime instrumentation (e.g., Puppeteer) can I use to deobfuscate JavaScript dynamically during execution?

26. How can I reconstruct client-side business logic from deobfuscated JavaScript, including API endpoints and user function mappings?

27. What patterns in deobfuscated JavaScript indicate potential vulnerabilities like XSS sinks or insecure API calls?

28. How can I use source maps (if available) to aid in deobfuscating JavaScript and understanding original source code?

29. What AI-driven scripts can I create to automate parts of JavaScript deobfuscation and identification in large bundles?

30. How can I validate deobfuscation results by cross-referencing with dynamic behavior in DevTools’ Network and Console tabs?

31. What ethical considerations should I keep in mind when deobfuscating JavaScript for bug bounty purposes, ensuring no modification of the target?

32. How can I handle large codebases (up to 700,000 lines) when identifying and deobfuscating backbone JavaScript files?

33. What tools or extensions in VS Code (e.g., ESLint) can help flag risky patterns in deobfuscated JavaScript?

34. How can I use Burp Suite to validate deobfuscated JavaScript insights by intercepting and manipulating related API calls?

35. What iterative steps should I follow to progressively deobfuscate a complex JavaScript bundle, starting from static analysis to dynamic testing?

36. How can I extract sensitive information like API keys or endpoints from deobfuscated JavaScript using pattern matching?

37. What AI prompts can I use to explain obfuscated code sections and suggest deobfuscation approaches?

38. How can I map user functionality from deobfuscated JavaScript, including event handlers and state management?

39. What challenges might I face with anti-debugging techniques in obfuscated JavaScript, and how can I bypass them ethically?

40. How can I document deobfuscation findings for inclusion in bug bounty reports, ensuring they support PoC development?

# Additional 40 Prompts for Parameters, User-Functionality, Debugging, Injection Points, Manual Testing Scope, Static/Dynamic Testing

41. How can I identify parameters in JavaScript functions that handle user inputs for potential injection points using static analysis in VS Code?

42. What techniques can I use to map user functionality in deobfuscated JavaScript, such as event handlers and API calls, for manual testing scope?

43. How can I debug JavaScript parameters in DevTools’ Console to identify reflected injection points during dynamic testing?

44. What static testing methods can I apply to JavaScript to detect parameter-based vulnerabilities like XSS or SQLi?

45. How can I use VS Code debugging to trace user functionality parameters in obfuscated code?

46. What manual testing scope should I define for JavaScript parameters handling sensitive data like passwords or tokens?

47. How can I identify injection points in JavaScript parameters using dynamic testing with Burp Suite interception?

48. What user functionality mappings can I extract from deobfuscated JavaScript for comprehensive manual testing?

49. How can I debug parameter flow in JavaScript using DevTools’ Sources tab for static and dynamic analysis?

50. What techniques detect reflected parameters in JavaScript that could lead to injection vulnerabilities?

51. How can I scope manual testing for JavaScript user functionality parameters in large codebases?

52. What static analysis tools in VS Code help identify parameter injection points in JavaScript?

53. How can I dynamically test JavaScript parameters for user functionality bypasses using Console commands?

54. What debugging workflows in DevTools reveal parameter-based injection points during testing?

55. How can I map user functionality parameters in JavaScript for targeted manual testing scope?

56. What static testing patterns identify dangerous parameters in deobfuscated JavaScript?

57. How can I use Burp Suite to test parameter injection points identified in JavaScript static analysis?

58. What user functionality debugging techniques in VS Code help uncover parameter vulnerabilities?

59. How can I identify reflected injection points in JavaScript parameters through dynamic testing?

60. What manual testing scope includes parameter validation in JavaScript user functionality?

61. How can I debug JavaScript parameters for static analysis of injection risks?

62. What techniques map user functionality parameters for comprehensive dynamic testing?

63. How can I identify parameter injection points in JavaScript using Console debugging?

64. What static testing methods validate JavaScript parameters for user functionality?

65. How can I scope manual testing for parameter-based vulnerabilities in deobfuscated JavaScript?

66. What debugging tools in DevTools help trace parameter flow in JavaScript?

67. How can I detect reflected parameters in JavaScript through static analysis?

68. What user functionality mappings include parameter injection points for manual testing?

69. How can I use VS Code for debugging JavaScript parameters in dynamic testing scenarios?

70. What techniques identify injection points in JavaScript parameters using Burp Suite?

71. How can I map user functionality parameters for static testing scope?

72. What debugging workflows reveal parameter vulnerabilities in JavaScript?

73. How can I identify reflected injection points in deobfuscated JavaScript parameters?

74. What manual testing scope covers parameter validation in user functionality?

75. How can I debug JavaScript parameters for dynamic analysis of injection risks?

76. What static testing patterns detect dangerous parameters in JavaScript?

77. How can I use Console commands to test parameter injection points?

78. What user functionality debugging includes parameter flow tracing?

79. How can I scope manual testing for JavaScript parameter vulnerabilities?

80. What comprehensive debugging approach combines static and dynamic testing for JavaScript parameters and user functionality?