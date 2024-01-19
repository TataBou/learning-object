Create a Moodle Page with the HTML 5 code as the content
<space>
Copy the URL (not the iframe embed code) of the H5P I want to embed/time, and I edit the HTML to include this (line #19 of the page code)
Adjust the width and height of the H5P in the code – again it’s commented – I get these values from the H5P iframe embed code (lines #22 and #23)
Adjust the timing to my preference (it’s in seconds) – line #9
Save the page
Hide/make available the H5P itself
 

You can edit the message that appears when the time is up. The code automatically replaces the H5P iframe with the ‘times up’ message once the timer hits 0 (line #44)

width and height 
22-23
    iframe.setAttribute("width", 50%");
    iframe.setAttribute("height", "100%"); works

timing 
9
60; // 60 seconds
