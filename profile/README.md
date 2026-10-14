# RayonAPI

RayonAPI generates F5 Shape request headers from client-supplied protection JavaScript,
browser profiles and exact request context.

[Documentation](https://docs.rayonapi.com/) · [Quickstart](https://docs.rayonapi.com/quickstart) · [Material preparation](https://docs.rayonapi.com/material)

1. Collect the required raw protection JavaScript, measured browser profile and browser-visible cookies in your own client.
2. Call the API or an SDK to generate six fresh headers for the exact request.
3. Apply the returned headers and send the request through your client and session.

## Repositories

| Repository | Purpose | Install |
| --- | --- | --- |
| [rayon-sdk-py](https://github.com/Rayon-API/rayon-sdk-py) | Python SDK | `python -m pip install rayon-sdk-py` |
| [rayon-sdk-js](https://github.com/Rayon-API/rayon-sdk-js) | JavaScript and TypeScript SDK | `npm install rayon-sdk-js` |
| [rayon-examples](https://github.com/Rayon-API/rayon-examples) | SDK integration examples | |
| [docs](https://github.com/Rayon-API/docs) | Documentation and API reference | |

[Support](mailto:support@rayonapi.com) · [Discord](https://discord.gg/TwhkJNyHWs)
