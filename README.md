# Robi & Airtel Number Checker (GitHub Pages)

## Deploy
1. Create a GitHub repository.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. Save and wait for GitHub Pages to publish.

## API note
This demo uses the endpoint visible in the referenced public source:
`https://da-api.robi.com.bd/da-nll/free-msisdn/get-msisdn-list`

It sends POST JSON `{ "msisdn": "...", "brand": "AIRTEL" | "ROBI", "simCategory": "PREPAID" }`.
Availability, CORS, and permitted use must be confirmed with the API owner. The UI limits each run to 500 checks and waits between requests. Do not add secrets to client-side code.
