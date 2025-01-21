# Lua pairs Iterator Bug

This repository demonstrates a potential issue with Lua's `pairs` iterator when used with deeply nested tables or tables containing a mix of key types.  Under certain circumstances, `pairs` might not correctly iterate through all elements or could even lead to an infinite loop, resulting in unexpected program behavior.

The `bug.lua` file contains code that illustrates the problem. The `bugSolution.lua` file provides a workaround to address this issue, ensuring reliable and complete iteration.

**Note:** The specific conditions that trigger this behavior might depend on the Lua interpreter version and system resources.  The example provided demonstrates a potential scenario where the problem can manifest.