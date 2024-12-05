# XSS Vulnerability in HTML using innerHTML

This repository demonstrates a common yet easily overlooked security vulnerability in HTML: using `innerHTML` with unsanitized user-supplied data.  This can lead to Cross-Site Scripting (XSS) attacks, allowing malicious actors to inject JavaScript code into your web page.

The `bug.html` file shows the vulnerable code, while `solution.html` demonstrates a safer alternative using `textContent`.