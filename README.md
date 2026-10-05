# GetInvoice public instruction and policy pages

Static instructions for the privately used desktop tool. These pages do not operate an online invoice service, launch desktop software automatically, receive OAuth callbacks, or revoke authorization themselves.

Intuit app URL fields (after deployment):

- Host domain: shawn-zhai-px.github.io
- Launch URL: https://shawn-zhai-px.github.io/getinvoice-policy/index.html
- Disconnect URL: https://shawn-zhai-px.github.io/getinvoice-policy/disconnect.html
- Connect/Reconnect URL: https://shawn-zhai-px.github.io/getinvoice-policy/connect.html
- EULA: https://shawn-zhai-px.github.io/getinvoice-policy/license.html
- Privacy: https://shawn-zhai-px.github.io/getinvoice-policy/privacy.html

The OAuth redirect registered for the Playground workflow is separate: https://developer.intuit.com/v2/OAuth2Playground/RedirectUrl . These informational app URLs do not replace it. Production acceptance of this internal-use workflow is subject to Intuit assessment; do not claim an automatic browser-based workflow exists.
