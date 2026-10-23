# DealPause — Second-Hand Deal Safety Copilot

**Pause. Verify. Deal safer.**

DealPause is a privacy-focused web application that helps people identify potentially risky requests when buying or selling second-hand phones, laptops, and other electronic devices.

Instead of simply labelling a message as suspicious, DealPause highlights the phrases that triggered a warning, explains the possible risk, and suggests practical next steps before users pay, meet someone, or hand over an item.

## 🌐 Live Demo

**Try DealPause:** https://dealpause.netlify.app/

## 💡 Inspiration

Second-hand transactions can be affordable and convenient, but they can also expose people to advance-payment scams, requests for OTPs or UPI PINs, deceptive QR-code instructions, fake payment screenshots, and suspicious application downloads.

People may not always recognize these warning signs, particularly when someone pressures them to act quickly.

DealPause was created to make these situations easier to understand. The goal is to help people pause, examine the available evidence, and make more informed decisions without relying on unexplained risk scores or fear-based warnings.

## ✨ Features

### 1. Explainable Message Safety Analysis

Paste a transaction message and analyze it using a transparent, rule-based detection engine.

The application checks for patterns associated with:

- Advance-payment requests and reservation deposits.
- OTP, UPI PIN, and credential requests.
- Deceptive QR-code and payment instructions.
- Unknown APK downloads and remote-access applications.
- Fake payment screenshots and unverified payment claims.
- Artificial urgency, coercion, and pressure to avoid marketplace protections.

### 2. Evidence-Based Findings

DealPause connects its findings to the specific phrases that triggered them.

Each finding provides an explanation of the concern, a severity indicator, and a recommended action.

The results are designed to communicate uncertainty rather than automatically accuse someone of fraud.

### 3. Buyer and Seller Context

Select your role as either a buyer or a seller and choose the current transaction stage:

1. First Contact
2. Discussing Deal
3. Before Meeting
4. Inspecting Item
5. Arranging Payment
6. Confirming Exchange

Recommendations and safety checklist items adapt to the selected context.

### 4. Safe-Reply Generator

Generate polite, practical responses to potentially unsafe requests.

Users can edit the suggested response and copy it to use in their own conversation.

### 5. Interactive Safety Checklist

Follow useful checks for different transaction stages, including arranging a meeting, inspecting a device, verifying payment, and completing an exchange.

Checklist progress updates as items are completed.

### 6. Safety Guide and Official Resources

Explore guidance for common second-hand transaction risks and access relevant resources, including India's National Cyber Crime Reporting Portal.

### 7. Privacy-Focused Design

The application is designed to perform its core message analysis locally in the browser without requiring a paid AI API or sending pasted messages to an external AI service.

### 8. Responsive Interface

DealPause includes a custom visual identity, original SVG branding, an animated CSS 3D-inspired hero illustration, and responsive layouts for desktop and mobile devices.

## 🛠️ Built With

- **React** — component-based user interface.
- **TypeScript** — typed application logic.
- **Vite** — development server and production build tooling.
- **CSS** — custom styling, responsive layouts, and animations.
- **Lucide React** — interface icons.
- **Vitest** — automated testing.

The safety engine uses deterministic, rule-based analysis rather than relying on a remote AI model.

## ⚙️ How It Works

1. Select your buyer or seller role.
2. Choose the stage of the transaction.
3. Paste a message or load a fictional example.
4. Run the safety analysis.
5. Review the highlighted evidence and explanations.
6. Follow the recommended safety steps or generate a reply.
7. Use the checklist to remember important transaction checks.

## 🚀 Run Locally

### Prerequisites

Install a recent compatible version of Node.js and npm.

### Installation

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Navigate into the project directory:

```bash
cd dealpause
```

Install the dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL printed in your terminal.

### Available Commands

Run the automated tests:

```bash
npm test
```

Run the linter:

```bash
npm run lint
```

Create a production build:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## ☁️ Deployment

DealPause is configured for static deployment using Netlify or Vercel.

### Netlify

1. Push the project to a GitHub repository.
2. Sign in to Netlify and import the repository.
3. Set the build command to `npm run build`.
4. Set the publish directory to `dist`.
5. Deploy the application.

### Vercel

1. Import the GitHub repository into Vercel.
2. Select Vite as the framework when detected.
3. Set the build command to `npm run build`.
4. Set the output directory to `dist`.
5. Deploy the application.

The project is designed to operate without mandatory API keys or environment variables.

## 🔐 Privacy and Responsible Design

DealPause is a decision-support tool, not a definitive scam detector.

Its rule-based engine does not verify a person's identity, authenticate a payment, access bank accounts, or consult a live fraud-intelligence database.

Important limitations:

- Legitimate messages may trigger warnings.
- New or unfamiliar scam techniques may go undetected.
- A message with no detected warning signs is not guaranteed to be safe.
- Risk indicators are heuristic assessments, not statistically calibrated probabilities.
- Users must independently verify payment, identity, and transaction details.

The application uses fictional examples for demonstration and avoids automatically opening links found in analyzed messages.

## 🧪 Testing

The project includes automated tests for the message-analysis engine and selected components and page workflows.

Testing should cover both suspicious messages and harmless transactions to evaluate detection behavior and reduce unnecessary warnings.

To run the tests locally:

```bash
npm test
```

Type checking and production-build verification should also be performed before deployment.

## 🏆 Hackathon Project

**Built for:** SafeSpace Hacks 2026

**Challenge:** Build something that helps people, communities, or systems stay safer.

**Focus areas:** Cybersecurity, privacy, scam awareness, consumer safety, and responsible software design.

DealPause aims to demonstrate how an accessible, explainable, privacy-conscious tool can help users recognize transaction warning signs and make more informed decisions.

## 🔮 What's Next

Potential future improvements include:

- Expanding the collection of realistic test messages.
- Improving detection of ambiguous wording and spelling variations.
- Reducing false positives through systematic testing.
- Improving accessibility and mobile usability.
- Expanding context-aware transaction guidance.

Future improvements will prioritize reliability, privacy, and useful explanations over unnecessary feature complexity.

## 🙌 Acknowledgements

This project was developed with AI coding assistance.

Third-party libraries and other reused components should be credited according to their respective licenses and included in the project's dependency records.

## 📄 License

Choose and add an appropriate open-source license before publicly licensing the repository. Until a license is added, do not assume that others have permission to reuse the source code.

---

**DealPause — Pause. Verify. Deal safer.**
