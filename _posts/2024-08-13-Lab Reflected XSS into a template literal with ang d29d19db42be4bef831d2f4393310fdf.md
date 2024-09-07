# Lab: Reflected XSS into a template literal with angle brackets, single, double quotes, backslash and backticks Unicode-escaped

---

![Untitled](Lab%20Reflected%20XSS%20into%20a%20template%20literal%20with%20ang%20d29d19db42be4bef831d2f4393310fdf/Untitled.png)

after making a search we can see a <script> tag: 

![Untitled](Lab%20Reflected%20XSS%20into%20a%20template%20literal%20with%20ang%20d29d19db42be4bef831d2f4393310fdf/Untitled%201.png)

as we can see what ever our search term is is being reflected inside of the string literal. 

and 

using ${funciton} will execute javascript without escaping the string literal. 

so our payload can be 

```jsx
${alert(1)}

```

![Untitled](Lab%20Reflected%20XSS%20into%20a%20template%20literal%20with%20ang%20d29d19db42be4bef831d2f4393310fdf/Untitled%202.png)