# Resume source

`resume.html` is the source of `../Rodrigo_Barreto_Resume.pdf`. After editing it, regenerate the PDF from this folder with headless Chrome:

```bash
"/c/Program Files/Google/Chrome/Application/chrome.exe" --headless=new --disable-gpu --no-pdf-header-footer --print-to-pdf="../Rodrigo_Barreto_Resume.pdf" "file:///$PWD/resume.html"
```

Check that the PDF still fits on one page.
