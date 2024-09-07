# [XSS] Lab: Reflected XSS into a JavaScript string with angle brackets HTML encoded

---

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20into%20a%20JavaScript%20string%20w%2011f4c5dffabc4305a14b616e7cb7b6a7/Untitled.png)

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20into%20a%20JavaScript%20string%20w%2011f4c5dffabc4305a14b616e7cb7b6a7/Untitled%201.png)

so again we’re being enclosed within single quotes 

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20into%20a%20JavaScript%20string%20w%2011f4c5dffabc4305a14b616e7cb7b6a7/Untitled%202.png)

so I did a view input until I got to know that it didn't encode ‘ ; - or ( ) characters so we can effectively escape this javascript string by commenting out the ending of it. 

so the payload was

```jsx
'-alert(1);//
```

![Untitled](%5BXSS%5D%20Lab%20Reflected%20XSS%20into%20a%20JavaScript%20string%20w%2011f4c5dffabc4305a14b616e7cb7b6a7/Untitled%203.png)