# [XSS] Lab: Stored XSS into anchor href attribute with double quotes HTML-encoded

---

![Untitled](%5BXSS%5D%20Lab%20Stored%20XSS%20into%20anchor%20href%20attribute%20wi%20b2fa26213f2e496d978f2cccddbbf8ba/Untitled.png)

since the lab mentions clicking on the author name and it uses a href since the website is not enforcing a website input therefore it doesn't [HTTP://websitename.com](HTTP://websitename.com) 

so because of this, we can use this input with the javascript: protocol 

so for the website we input “javascript:alert(1)” 

![Untitled](%5BXSS%5D%20Lab%20Stored%20XSS%20into%20anchor%20href%20attribute%20wi%20b2fa26213f2e496d978f2cccddbbf8ba/Untitled%201.png)

the [HTTP://test.com](HTTP://test.com) at the end it optional but we are able to add it since we comment it out with the ‘//’

![Untitled](%5BXSS%5D%20Lab%20Stored%20XSS%20into%20anchor%20href%20attribute%20wi%20b2fa26213f2e496d978f2cccddbbf8ba/Untitled%202.png)