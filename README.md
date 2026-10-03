# SignalShield

SignalShield is a hackathon prototype that checks social media messages for common social-engineering warning signs.

## What it checks

- Urgent language and pressure to act quickly
- Threats such as account suspension
- Claims to represent an authority
- Unexpected prizes or rewards
- Requests for passwords, codes, bank details, or payment
- Suspicious links

The demo highlights phrases it finds, gives a risk indicator, and suggests a safer next step.

## How to use

1. Open the app.
2. Paste a message into the text box, or choose one of the sample messages.
3. Click **Analyze message**.
4. Review the risk indicator and the signals found.

## Run the project

Open `index.html` in a web browser. No installation is required.

## Publish with GitHub Pages

1. Upload `index.html` and `README.md` to your GitHub repository.
2. Open the repository's **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Choose the `main` branch and the `/(root)` folder, then click **Save**.

## Important note

This prototype uses simple text-matching rules. It is not a trained or validated AI model. A low risk result does not guarantee that a message is safe.

## Future improvements

- Test the detector with a labeled set of simulated messages.
- Measure how often it catches scams and flags ordinary messages.
- Add an NLP model while keeping the explanations clear.
