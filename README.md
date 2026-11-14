## Engineering projects

**[Dispute Desk](https://github.com/ihussain2323/dispute-desk)** takes a payment dispute from a voice call to a confirmed case using Parakeet v3, Supertonic 3, and FastAPI. [Hear the agent read back a disputed $6.75 charge](https://github.com/ihussain2323/dispute-desk/blob/main/demo/call.wav) and [inspect the confirmed case](https://github.com/ihussain2323/dispute-desk/blob/main/demo/case.json).

**[Turnscope](https://github.com/ihussain2323/turnscope)** measures where a voice agent interrupts a caller and how long the caller waits for a reply. Its speech benchmark compares Parakeet v3 and Whisper on the same six payment-support requests at three noise levels. [Listen to a clip](https://github.com/ihussain2323/turnscope/blob/main/speech/dispute.wav) or [inspect how noise changed the transcripts](https://github.com/ihussain2323/turnscope/blob/main/measurements/parakeet-v3.json).

**[Payout Diff](https://github.com/ihussain2323/payout-diff)** traces a bank deposit to the charges, fees, and refunds that funded it. In the [sample exports](https://github.com/ihussain2323/payout-diff/tree/main/examples), two payouts compete for one $45 deposit and a separate payout lands one cent short. The report preserves the evidence for both exceptions.

**[Relay Recovery](https://github.com/ihussain2323/relay-recovery)** explores what happens when a customer webhook processes a request and loses the response. Its [outage exercise](https://github.com/ihussain2323/relay-recovery/blob/main/soak.py) drives three competing workers against a local receiver and checks the downstream side effects after retries and worker crashes.
