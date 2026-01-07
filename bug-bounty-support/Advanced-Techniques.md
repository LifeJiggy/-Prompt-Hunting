# Advanced Techniques Prompts

This file contains ~40 powerful prompts for advanced techniques in bug bounty hunts. These prompts incorporate content from all your existing .txt files, focusing on symbolic execution, AI integration, Webpack handling, and cutting-edge methods.

From Master-prompt.txt and Project.txt:
- Webpack bundle formats (IIFE, UMD, ESM, CommonJS modules, chunk loading), Obfuscation techniques (name mangling, control flow flattening, string encryption, VM-based virtualization), Framework/library-specific code patterns (React JSX transpilation, Angular decorators, Node.js server bundles), Bundling artifacts like chunking, code splitting, lazy loading, polyfills.

- AST (Abstract Syntax Tree) Parsing & Manipulation: Using robust parsers (e.g., Babel, SWC, Esprima, Acorn), Control Flow & Data Flow Analysis: To reconstruct logical flow, remove dead/opaque code, Variable/Function Renaming with Context Awareness: Leverage scope and usage analysis for renaming meaningful names, Dependency Graph and Module Linking: Understand chunk dependencies, module graph reconstructed from Webpack manifests.

- API Call & Client Logic Extraction: Detect API requests patterns (fetch, axios, XMLHttpRequest), identify event handlers, UI state manipulations, Hybrid Symbolic Execution + Heuristic Analysis: Execute code snippets symbolically for complex obfuscations, Dynamic Analysis Integration: Hook runtime JS instrumentation (via Chrome, Firefox DevTools Protocol, Puppeteer) to observe live behavior and feed back to static analysis.

From other files: Integrated advanced analysis, symbolic execution, and AI-driven methods.

1. How can I use AST parsing to analyze obfuscated JavaScript for vulnerability patterns?

2. What techniques can I apply for symbolic execution in JavaScript deobfuscation?

3. How can I reconstruct Webpack bundles from chunked files?

4. What AI models can I use for pattern recognition in JavaScript analysis?

5. How can I handle VM-based obfuscation in JavaScript?

6. What dynamic analysis hooks can I implement with Puppeteer?

7. How can I use data flow analysis to trace sensitive data in JS?

8. What advanced Regex patterns work for complex obfuscation?

9. How can I integrate symbolic execution with DevTools debugging?

10. What AI prompts optimize vulnerability heatmaps?

11. How can I reconstruct module dependencies in bundled JS?

12. What techniques handle lazy loading in Webpack bundles?

13. How can I use AST manipulation for code transformation?

14. What AI-driven scripts automate PoC generation?

15. How can I analyze control flow flattening in obfuscated code?

16. What runtime instrumentation reveals hidden behaviors?

17. How can I use symbolic execution for API endpoint discovery?

18. What AI techniques detect framework-specific vulnerabilities?

19. How can I handle polyfills in Webpack analysis?

20. What advanced methods reconstruct original source from bundles?

21. How can I use data flow graphs for impact analysis?

22. What AI models assist in code flow tracing?

23. How can I integrate dynamic and static analysis seamlessly?

24. What techniques handle ESM modules in bundles?

25. How can I use symbolic execution for exploit validation?

26. What AI prompts generate remediation strategies?

27. How can I reconstruct client-side state from obfuscated JS?

28. What advanced tools complement Burp Suite for JS analysis?

29. How can I use AST for dependency graph visualization?

30. What AI-driven heatmaps prioritize attack vectors?

31. How can I handle CommonJS in Webpack reconstruction?

32. What symbolic execution tools work for JavaScript?

33. How can I integrate AI with regex for pattern matching?

34. What techniques handle string encryption in JS?

35. How can I use runtime hooks for behavior observation?

36. What AI models predict vulnerability chains?

37. How can I reconstruct Angular decorators from bundles?

38. What advanced methods handle React JSX in obfuscated code?

39. How can I use symbolic execution for Node.js bundles?

40. What comprehensive advanced workflow maximizes bug discovery?