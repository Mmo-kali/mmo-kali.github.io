# [XSS] Lab: DOM XSS in innerHTML sink using source location.search

---

![Untitled](%5BXSS%5D%20Lab%20DOM%20XSS%20in%20innerHTML%20sink%20using%20source%20l%20e11659210ee645ba8c21e993072fb3ef/Untitled.png)

![Untitled](%5BXSS%5D%20Lab%20DOM%20XSS%20in%20innerHTML%20sink%20using%20source%20l%20e11659210ee645ba8c21e993072fb3ef/Untitled%201.png)

![Untitled](%5BXSS%5D%20Lab%20DOM%20XSS%20in%20innerHTML%20sink%20using%20source%20l%20e11659210ee645ba8c21e993072fb3ef/Untitled%202.png)

we were able to inject HTML

 

```jsx
"><u> test123 
```

![Untitled](%5BXSS%5D%20Lab%20DOM%20XSS%20in%20innerHTML%20sink%20using%20source%20l%20e11659210ee645ba8c21e993072fb3ef/Untitled%203.png)

since we’re using inner HTML <script> tag will not work so we need to try a different event handler. 

![Untitled](%5BXSS%5D%20Lab%20DOM%20XSS%20in%20innerHTML%20sink%20using%20source%20l%20e11659210ee645ba8c21e993072fb3ef/Untitled%204.png)

but no alert occurred 

![Untitled](%5BXSS%5D%20Lab%20DOM%20XSS%20in%20innerHTML%20sink%20using%20source%20l%20e11659210ee645ba8c21e993072fb3ef/Untitled%205.png)

![Untitled](%5BXSS%5D%20Lab%20DOM%20XSS%20in%20innerHTML%20sink%20using%20source%20l%20e11659210ee645ba8c21e993072fb3ef/Untitled%206.png)

![Untitled](%5BXSS%5D%20Lab%20DOM%20XSS%20in%20innerHTML%20sink%20using%20source%20l%20e11659210ee645ba8c21e993072fb3ef/Untitled%207.png)