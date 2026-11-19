# Insurance Proposal Studio

A static, browser-local insurance proposal tool. Open `dist/index.html` in a modern browser or serve `dist` with any static web server. No account, backend, or build step is required. Saved customer data is stored in localStorage on the current browser and device; clearing browser data removes it. Use Print / Save PDF from the preview to create a PDF.

Premium uses the supplied age rates for a 20-year term, +1.25 accidental-death rate, −0.50 for sum assured of at least PKR 300,000, and a PKR 100 fee. Ages under 20 use the age-20 rate. Ages above 55 are unsupported. Calculations use rounded whole rupees. The proposal is illustrative and benefits are subject to policy terms and approval.

This website is independent of the Android app and can be deployed with GitHub Pages by publishing the `dist` directory through a workflow or copying its contents to the root of a Pages branch.
