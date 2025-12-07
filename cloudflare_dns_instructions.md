# Cloudflare DNS Configuration for itstysonchen.me

To set up your custom domain `itstysonchen.me` with GitHub Pages using Cloudflare, please follow these steps:

1.  **Log in to Cloudflare:** Go to the Cloudflare website and log in to your account.
2.  **Select your Domain:** From your Cloudflare dashboard, select the domain `itstysonchen.me`.
3.  **Go to DNS Settings:** Click on the "DNS" icon or tab to access your DNS management page.

4.  **Add/Edit DNS Records:** You will need to add two types of records:

    ### For the Apex Domain (itstysonchen.me)

    You have two options here. The `CNAME` flattening method is generally preferred with Cloudflare.

    #### Option A: CNAME Flattening (Recommended with Cloudflare)
    This is often done by adding an `A` record, and Cloudflare will automatically handle the flattening to your GitHub Pages URL.

    *   **Type:** `A`
    *   **Name:** `@` (or `itstysonchen.me`)
    *   **IPv4 address:**
        *   `185.199.108.153`
        *   `185.199.109.153`
        *   `185.199.110.153`
        *   `185.199.111.153`
    *   **TTL:** Automatic (or default)
    *   **Proxy Status:** Ensure the orange cloud is **enabled** (Proxied).

    You will need to add four separate `A` records, one for each IP address.

    #### Option B: ALIAS/ANAME (If supported, less common to manually add)
    Some DNS providers (including Cloudflare internally for apex domains) allow an `ALIAS` or `ANAME` record which behaves like a `CNAME` for the apex domain. If you see this option for the apex domain, you can use:

    *   **Type:** `ALIAS` or `ANAME`
    *   **Name:** `@` (or `itstysonchen.me`)
    *   **Target:** `tysonchen.github.io` (Replace `tysonchen` with your GitHub username if it's different)
    *   **TTL:** Automatic
    *   **Proxy Status:** Ensure the orange cloud is **enabled** (Proxied).

    ### For the `www` Subdomain (www.itstysonchen.me)

    *   **Type:** `CNAME`
    *   **Name:** `www`
    *   **Target:** `tysonchen.github.io` (Replace `tysonchen` with your GitHub username if it's different)
    *   **TTL:** Automatic (or default)
    *   **Proxy Status:** Ensure the orange cloud is **enabled** (Proxied).

5.  **Save Changes:** After adding all the records, make sure to save your DNS configuration.

6.  **GitHub Pages Settings:**
    *   Go to your GitHub repository (`itstysonchenme`).
    *   Navigate to **Settings** > **Pages**.
    *   Under "Custom domain", enter `itstysonchen.me` and click "Save". GitHub will check your DNS records. If they are correctly configured, it will show a message indicating that your custom domain is ready.

7.  **Propagation Time:** DNS changes can take some time (up to 48 hours, but usually faster with Cloudflare) to propagate across the internet. Be patient if the changes don't appear immediately.

By following these steps, your `itstysonchen.me` domain should successfully point to your GitHub Pages site through Cloudflare.