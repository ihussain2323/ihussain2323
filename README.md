## Engineering projects

**[Turnscope](https://github.com/ihussain2323/turnscope)** measures where a voice agent interrupts a caller and how long the caller waits for a reply. A second experiment runs Whisper on six synthetic payment-support requests. [Listen to a clip](https://github.com/ihussain2323/turnscope/blob/main/speech/dispute.wav) or [inspect how noise changed the transcripts](https://github.com/ihussain2323/turnscope/blob/main/measurements/tiny-en.json).

**[Payout Diff](https://github.com/ihussain2323/payout-diff)** traces a bank deposit to the charges, fees, and refunds that funded it. In the [sample exports](https://github.com/ihussain2323/payout-diff/tree/main/examples), two payouts compete for one $45 deposit and a separate payout lands one cent short. The report preserves the evidence for both exceptions.

**[Relay Recovery](https://github.com/ihussain2323/relay-recovery)** explores what happens when a customer webhook processes a request and loses the response. Its [outage exercise](https://github.com/ihussain2323/relay-recovery/blob/main/soak.py) drives three competing workers against a local receiver and checks the downstream side effects after retries and worker crashes.
