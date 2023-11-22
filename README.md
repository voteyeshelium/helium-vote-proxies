# helium-vote-proxies

Definitions of public wallets available for Proxy Voting

## Adding a Proxy

To add a proxy, fork this repository and make a pull request containing the following:

- An entry in `proxies.json`
- Any necessary files and assets in a folder

First, add the proxy to to `proxies.json`. Each proxy should have the following properties:

## | Property | Description |

| name | The name of the proxy. This could be the name of a person, or a voting entity. |
| image | A profile picture for the proxy. This will be displayed in the proxy discovery UI and in search. This should be a file path to the jpeg or png. |
| description | A short description of the proxy. This will be displayed in the proxy discovery UI
| detail | A filepath to a markdown file containing a more detailed biography of the proxy. This should describe voting philosophies, and any other relevant information to those choosing to delegate. This will be displayed in the proxy discovery UI

### Example

You can see the `example` proxy listed in `proxies.json` as follows:

```
{
  "wallet": "ex1iPHN3wCAUSwPrNENvxMW1w6ggZRQwYUmQwmAn646.json",
  "name": "Example Proxy",
  "image": "./example/image.png",
  "description": "Example proxy voter",
  "detail": "./example/detail.md"
}
```

You can further check the `example` subdirectory to see examples of the image and detail.