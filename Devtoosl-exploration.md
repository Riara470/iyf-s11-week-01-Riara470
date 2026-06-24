Website 1: https://example.com
Tags used 
1. <!DOCTYPE html> - Declares HTML5
2. <html> - Root element
3. <head> - Contains metadata
4. <meta charset="utf-8"> - Character encoding
5. <title> - Page title “Example Domain”
6. <style> - Inline CSS for layout
7. <body> - Main content wrapper
8. <div> - Container for the content box
9. <h1> - “Example Domain” heading
What is the page title?
"Example Domain"
How many headings are there?
there is 1 heading <h1> "Example Domain"

Website 2: https://developer.mozilla.org
Find the navigation menu - what tag is it wrapped in?
<nav> - wrapsthe whole navigation section
 <ul> and <li> -wraps unordered list and listed items
How is the search bar structured?
   1. <form> - Wraps everything. Has role="search" so screen readers know it’s a search form. Action points to /en-US/search
2. <label> - Linked to input with for="topq". Usually visually hidden but accessible. Text like “Search MDN”
3. <input type="search"> - The actual search field. Key attributes: 
   - type="search" gives you the built-in clear "x" button on mobile
   - name="q" - that’s the query param sent to server
   - placeholder="Search MDN"
   - id="topq" to match the label
4. <button type="submit"> - Submit button with a magnifying glass icon, usually SVG inside
What happens when you hover over links (check the styles)?
1. Color change: Link text color shifts. Main nav links go from dark gray to MDN’s blue #1b1b1b → #0081a7 
2. Underline/background: Top nav links get an underline or bottom border appear. Side nav links get a light gray background #f9f9fb 
3. Cursor: Changes to pointer hand, standard for links

website 3: youtube
Identify 5 different HTML elements
<ytd-app>
<input type="text">
<video>
<img>
<button>
Find a form element and list its inputs
1. <input type="text" id="search" name="search_query">  
2. <input type="hidden" name="sp">
<img width="519" height="338" alt="youtube" src="https://github.com/user-attachments/assets/2c43fc20-1224-4d17-8fb3-e1dd01ba96d7" />

