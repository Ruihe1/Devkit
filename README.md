# 🧰 DevKit

Free, private toolbox for developers, with an animated space background. It runs entirely in your browser, and nothing is uploaded anywhere.

## Tools
JSON formatter · Base64 · URL encode/decode · SHA hash generator · UUID generator · Regex tester · Timestamp converter · JWT decoder · Text diff · Password generator

## Use it
Open `index.html` in any browser, or host it free on GitHub Pages (Settings → Pages → branch `main`, folder `/ (root)`).

- Light and dark mode switch (top right)
- 🎬 Scene button hides the tools so you can watch the animation

## Python version
`app.py` is an alternative version built with Streamlit:
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Contributing
New tools are easy to add: write a tool object in the `TOOLS` array in `index.html`. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Roadmap
- [ ] YAML/TOML/JSON converter
- [ ] Cron expression explainer
- [ ] Markdown preview
- [ ] Color converter
- [ ] SQL formatter

## License
MIT
