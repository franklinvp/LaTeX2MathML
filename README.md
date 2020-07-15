# LaTeX2MathML

HTML page with Javascript that uses MathJax to transform LaTeX to MathML to input into DITA

You can download this page by running

```
git clone git@code.ssnc.global:Franklin.Pacheco/latex2mathml.git
```

You will see a directory called `latex2mathml`. Open the page `LaTeX2MathML.html` in a browser.
The conversion is done by making requests to cdnjs.cloudflare.com, which runs the MathJax script.
So, it requires internet connection.

If you want you can download MathJax too such that everythin runs locally.
Such that you don't need to modify the HTML download it inside the directory `latex2mathml`.
Download MathJax by running

```
git clone https://github.com/mathjax/MathJax.git MathJax
```

You will see a directory called `MathJax`.

