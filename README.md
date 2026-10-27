# Account Journey Score

**Try it:** https://pearlmcguire-gif.github.io/account-journey-dashboard/

An interactive demo that scores customer accounts across the whole journey, starting at the first discovery call instead of the first login.

With AI products, high usage no longer means a customer is getting value. This demo explores a different starting point: score what sales and Customer Success learn from discovery onward, track whether value is actually proven against a benchmark, and flag risk as soon as it appears instead of at renewal.

## What you can do in the demo

- **Change the weights** of five scores (value clarity and proof, sales and Customer Success alignment, readiness and onboarding, relationship depth, account stability) and watch 20 fictional accounts update.
- **Move Customer Success** to join during discovery, at contract signature, or after implementation, and see how many early flags go unseen.
- **Open any account** to see its score at every stage, the goals being tracked, usage compared with value, and its flags.
- **Use the learning loop**, which compares the accounts that went best with the ones that struggled and suggests new weights.

All companies, people and figures in the demo are fictional.

## How it's built

- A single static HTML page, hosted on **GitHub Pages**
- **PostHog** for cookieless usage analytics and an in-page feedback survey
- Designed and built with **Claude**, from the scoring model through the page and its accessibility checks

## Feedback

Every section of the demo has a **Feedback** button, and feedback is anonymous unless you add your name. If your browser blocks the form, it gives you a copy of your feedback to send directly.

## About

Concept and framework by **Pearl McGuire**, Customer Success. The criteria, scoring guides and discovery question set behind the scores are not included in this repository.

Want to talk it through? [Connect on LinkedIn](https://www.linkedin.com/in/pearlmcguire).

© 2026 Pearl McGuire. All rights reserved.
