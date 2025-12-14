### Phase 3: API and Network Analysis

**Task:** Use the Network tab in your DevTools to observe the API calls made during the login process.

**Deliverable:** A document (`api_analysis.md`) that details the login API call.

**Information to Capture:**
-   **Request URL:** `https://www.saucedemo.com/`
-   **Request Method:** `GET`
-   **Request Payload (Body):** What data is sent to the server? ❌ None (GET requests do not send a request body)
-   **Response Status Code (for a successful login):** `200 OK`
-   **Response Body (for a successful login):**
  <!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8"/>
        <link rel="icon" href="/favicon.ico"/>
        <meta name="robots" content="noindex">
        <meta name="viewport" content="width=device-width,initial-scale=1"/>
        <meta name="theme-color" content="#ffffff"/>
        <meta name="description" content="Sauce Labs Swag Labs app"/>
        <link rel="apple-touch-icon" href="/icon/icon-192x192.png"/>
        <link rel="manifest" href="/manifest.json"/>
        <script type="text/javascript">
            !function(n) {
                if ("/" === n.search[1]) {
                    var a = n.search.slice(1).split("&").map(function(n) {
                        return n.replace(/~and~/g, "&")
                    }).join("?");
                    window.history.replaceState(null, null, n.pathname.slice(0, -1) + a + n.hash)
                }
            }(window.location)
        </script>
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=DM+Sans:wght@400;500">
        <title>Swag Labs</title>
        <script defer="defer" src="/static/js/main.bcf4bc5f.js"></script>
        <link href="/static/css/main.8a7d64a1.css" rel="stylesheet">
    </head>
    <body>
        <noscript>You need to enable JavaScript to run this app.</noscript>
        <div id="root"></div>
    </body>
</html>


