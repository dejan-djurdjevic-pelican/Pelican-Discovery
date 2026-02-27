#  Pelican Discovery Dashboard

A live trading signal discovery gateway built for the Pelican ecosystem. This dashboard integrates with the Copy-Trade.io Identity Server to provide secure access to real-time performance metrics for top signal providers.

## 🚀 Features
* **Secure Authentication:** OpenID Connect (OIDC) integration via Pelican Secure Gateway.
* **Live Discovery:** Fetches top-performing strategies directly from the Copy-Trade API.
* **Dynamic UI:** * **Pelican Spotlight:** Highlights hand-picked featured signals.
    * **Monthly Leaders:** Automatically identifies the Top 10 performers by profit each month.
* **Smart Fallbacks:** Automatically handles missing profile imagery with professional placeholders.
* **Searchable Feed:** Real-time client-side filtering by signal name.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript.
* **Auth:** `oidc-client-js` for secure OAuth2 flows.
* **API:** RESTful integration with `papi.copy-trade.io`.
* **Hosting:** GitHub Pages.

## 🔑 Setup Note
This application requires an active API client configuration on the Pelican Identity Server. Ensure the `redirect_uri` in `index.html` matches your deployment environment.
