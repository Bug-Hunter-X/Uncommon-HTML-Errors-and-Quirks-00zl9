# Uncommon HTML Errors and Quirks

This repository demonstrates some uncommon HTML errors that might not immediately throw exceptions but lead to unexpected behavior in web applications.

The `bug.html` file contains the erroneous code.  `bugSolution.html` shows how to handle or prevent these issues.

**Errors Demonstrated:**

* **Accessing a non-existent attribute:**  Attempting to retrieve the value of an attribute that doesn't exist. Although this returns `null`, it's important to handle gracefully in your code.
* **Mismatched Tag:** Demonstrates the potential issue of having an incomplete opening tag.
* **Using an unknown HTML5 tag:** This may produce no error or unexpected behavior depending on the browser and HTML parser used.

**Solutions:**

* Always validate that attributes exist before accessing them.  Use appropriate error handling.
* Double-check HTML tags for proper formatting and closing.
* Stick to well-known HTML tags or ensure your browser/HTML parser supports your custom tags.

This example highlights that even seemingly innocuous coding mistakes in HTML can lead to subtle bugs. Careful coding and thorough testing are crucial.