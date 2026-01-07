# Specific Vulnerabilities Hunting Prompts

This file contains ~40 powerful prompts for hunting specific vulnerabilities in bug bounty hunts, focusing on XSS injection points, insecure API endpoints, authentication bypass logic, CSRF token manipulation, DOM-based vulnerabilities, client-side storage weaknesses, business logic flaws, CMD (Command Injection), BAC (Broken Access Control), IDOR (Insecure Direct Object Reference), and more. These prompts use advanced pattern matching, AST parsing, dependency analysis, code flow tracing, and sensitive information extraction, drawing from all your existing .txt files.

From Master-prompt.txt:
- JAVASCRIPT RECON ANALYSIS: Execute comprehensive security analysis of JavaScript files from target URLs using advanced static and dynamic analysis techniques. Systematically scan all client-side JavaScript (including Webpack bundles, minified code, source maps, and dynamic imports) to identify critical vulnerabilities including XSS injection points, insecure API endpoints, authentication bypass logic, CSRF token manipulation, DOM-based vulnerabilities, client-side storage weaknesses, and business logic flaws. Use advanced pattern matching, AST parsing, dependency analysis, and code flow tracing to extract sensitive information, hardcoded credentials, exposed API keys, and insecure configurations. Provide detailed vulnerability mapping, exploit POCs, and remediation strategies for all discovered security weaknesses in live JavaScript applications.

From other files: Integrated techniques for detection, exploitation, and ethical testing.

1. How can I use AST parsing to identify XSS injection points in JavaScript DOM manipulation code?

2. What Regex patterns can I apply to detect insecure API endpoints lacking authentication in JS files?

3. How can I trace code flow to uncover authentication bypass logic in client-side checks?

4. What dependency analysis reveals CSRF token manipulation vulnerabilities in API calls?

5. How can I use pattern matching to find DOM-based XSS sinks like innerHTML or document.write?

6. What techniques extract sensitive information from client-side storage weaknesses in localStorage?

7. How can I identify business logic flaws in JavaScript state management using code flow tracing?

8. What AST parsing detects CMD injection points in dynamically constructed commands?

9. How can I hunt for BAC by analyzing access control checks in JavaScript functions?

10. What dependency analysis uncovers IDOR vulnerabilities in API parameter handling?

11. How can I use code flow tracing to map XSS injection points from user input to DOM rendering?

12. What pattern matching identifies insecure API endpoints with missing CSRF tokens?

13. How can I extract hardcoded credentials from JavaScript using AST parsing?

14. What techniques detect authentication bypass logic in role-based client checks?

15. How can I trace CSRF token manipulation in form submissions using dependency analysis?

16. What Regex patterns find DOM-based vulnerabilities in event handlers?

17. How can I identify client-side storage weaknesses exposing session data?

18. What code flow tracing reveals business logic flaws in price calculations?

19. How can I detect CMD injection in JavaScript using pattern matching for exec calls?

20. What AST parsing uncovers BAC in permission validation functions?

21. How can I hunt IDOR by analyzing object ID parameters in API endpoints?

22. What advanced techniques combine AST and pattern matching for XSS detection?

23. How can I extract sensitive API keys from insecure endpoint configurations?

24. What dependency analysis identifies authentication bypass in multi-step flows?

25. How can I trace CSRF token weaknesses in AJAX requests?

26. What code flow tracing finds DOM-based XSS in template rendering?

27. How can I detect client-side storage leaks of PII using pattern matching?

28. What techniques identify business logic flaws in quantity limits?

29. How can I use AST parsing for CMD injection in Node.js bundles?

30. What dependency analysis reveals BAC in admin panel access?

31. How can I hunt IDOR in user profile endpoints with code flow tracing?

32. What Regex patterns detect insecure API endpoints with weak auth?

33. How can I extract sensitive information from exposed error messages?

34. What pattern matching finds CSRF token bypasses in forms?

35. How can I trace DOM-based vulnerabilities in React components?

36. What AST parsing identifies client-side storage manipulation?

37. How can I detect business logic flaws in discount calculations?

38. What techniques hunt CMD injection in shell command construction?

39. How can I use dependency analysis for BAC in role escalation?

40. What comprehensive hunting workflow targets all these vulnerabilities ethically?