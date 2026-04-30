# panda-session

> [!NOTE]
> This library has been archived, and there is no suggested replacement.

This javascript library lets tools reauthenticate users whose [pan-domain-authentication](https://github.com/guardian/pan-domain-authentication/) (or “panda”) cookies have expired, without reloading the page.

This is especially useful for client-side apps which do their own routing, because a user may navigate through multiple pages in a long session without the backend getting a chance to do an oauth redirect and refresh the cookie.

The way the app does this is by loading an iframe and reauthenticating without the user being aware of it. While this method still works, it is somewhat frowned upon, and so the library has been archived and we recommend not using it.

