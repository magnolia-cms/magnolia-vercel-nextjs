# Vercel Integration

## Pages and Components

The demo contains:

-   Basic page template
-   Contact page template
-   Header component
-   Paragraph component
-   Image component
-   List component
-   Item component (available inside List component)
-   Expander component

-   Navigation component

### DAM

In order for images to be displayed:
Open the Security app, open the `Roles` tab, edit the `rest-anonymous` role, go to `Web access` tab, `Add new` with this path `/dam/*` set to GET.

![Image Access for Anonymous](magnolia/_dev/README-security-anonymous-dam.png)

In `Access control lists` tab modify `Dam` workspace by allowing `Read-only` access to `Selected and sub nodes` to `/`.

### Next.js SSR

You will need to create a root page with the `Next.js SSR: Basic` template and name it `vercel-demo`.

### Manually:

Open the `Pages` app in Magnolia and **_click Add Page_** add either

-   A `Next.js SSR: Basic` **_template_** and name it `vercel-demo`

> The page name is important as the SPA's are hardcoded to treat those names as the base of the app.
