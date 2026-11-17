# sample-express

> [!WARNING]
> **This sample is retired and is no longer hosted.** The live demo that used to run on Heroku has been taken down, and the hardcoded environment key in these pages no longer accepts tokenization requests.
>
> This sample uses legacy Express with non-secure tokenization (environment key only, no nonce or signature). Non-secure tokenization was deprecated on October 31, 2026, with end of life on December 31, 2028. Do not use this code as the basis for a new integration.
>
> For new integrations, use the [Checkout SDK](https://developer.spreedly.com/docs/tokenization). If you maintain an existing Express integration, see the [Express payment form](https://developer.spreedly.com/docs/express-payment-form) guide for secure tokenization, and turn on Enhanced Security for your environment in app.spreedly.com.

An example implementation of a payment page using Spreedly Express.

A basic page is shown in `index.html`.

A page showing how a master form can also collect additional information is shown in `sample.html`.
