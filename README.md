<p align="center">
  <img src="logo.svg" alt="pay.lambda.digital" width="300" />
</p>
# pay.lambda.digital

Crypto payment infrastructure for modern businesses.

Embed a payment widget in minutes — your customers pay in crypto,
funds land directly in your wallet.

## What we do

- **Hosted checkout** — branded payment pages, no frontend work required
- **Simple API** — create a payment intent, get a checkout URL, receive a webhook
- **Non-custodial** — funds go straight to your wallet, we never hold them
- **Multi-chain** — EVM (BSC, Ethereum) and Tron supported

## For developers

```http
POST /v1/payment-intents
Authorization: Bearer sk_live_...

{
  "amount": 99.00,
  "currency": "USDT",
  "chain": "bsc",
  "metadata": { "orderId": "123" }
}
