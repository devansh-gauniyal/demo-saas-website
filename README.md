# LaunchPilot Demo Site

This is a small dummy SaaS website for testing MarketPilot AI.

It is intentionally imperfect so the marketing agent has real things to find:

- Missing meta descriptions
- Weak or duplicate titles
- Missing image alt text
- Thin content
- Missing canonical tags
- Missing schema markup
- Broken internal links

## Run Locally

Open `index.html` directly in a browser, or serve the folder:

```powershell
python -m http.server 5177
```

Then visit:

```text
http://localhost:5177
```

## Useful Test Pages

- `index.html` - homepage with missing meta description and missing image alt text
- `pricing.html` - pricing page with weak SEO structure
- `features.html` - feature page with thin content and missing schema
- `blog/seo-agent-checklist.html` - blog page with missing canonical and image alt text

## GitHub Connector Test Files

The `content/` folder has MDX files with `<img>` tags missing `alt`.

Those files are meant for MarketPilot's `add_alt_text` tool.

## Next Steps for Your Marketing Automation

Ready to transform your SaaS marketing? LaunchPilot AI offers powerful autonomous agents designed to accelerate growth for early-stage teams.

- Explore our full platform capabilities and agent features.
- Schedule a personalized demo to see LaunchPilot AI in action.
- Connect with our support team for tailored implementation guidance.
