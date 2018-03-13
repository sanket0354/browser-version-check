# browser-version-check
A small and fast javascript plugin to check if your website is compatible with the browser version. There are lot of cool plugins out there, but I have researched and added some of my own code implemented in pure simple javascript giving you full control over where and how to use it.

## Getting Started
The plugin is simple to use. See the instructions below.

### Step 1
Download the js files from repository and add them to your project

### Step 2
```<script src="<Path to browser-version-check.js"></script>```

### Step 3
Use this as your first call on your website - include it in script tag or a seperate js function of your own

```check_browser_support({chrome:"44.0.2403.133", internetExplorer: "10.0", firefox: "45.0", safari: "8.0"}```

The function will return true if browser's version is greater than or equal to passed parameters, false otherwise

For example,

&nbsp;&nbsp;if you include call the function with above mentioned browser version:

- you will get true, if your browser version for chrome is 44.0.2404.133 or 45.1.2 or 44.0.2403.134 (similarly for other browser)
- you will get false, if your browser version for chrome is 44.0.2403.132 or 42 (similarly for other browser)

Once you get true/false depending on browser, you can do whatever you want - display message or redirect to another page

## Acknowledgments
- Stack Overflow
