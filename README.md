# Shopify Developer Training Plan
A thorough Checklist of Shopify concepts every developer should know in the order they should learn them

## Contents
- [Theme Development](#theme-development)
- [App Development](#app-development)

## Theme Development

### Basics

1. Know how to create a development environment. [1](https://help.shopify.com/en/partners/dashboard/managing-stores/development-stores)

2. Understand the limitations of a development store including the use of the Bogus Payment Gateway. [2](https://help.shopify.com/en/partners/dashboard/managing-stores/test-orders-in-dev-stores#testing-using-shopifys-bogus-gateway)

3. Know how to utilize ThemeKit to sync your local development theme with the Shopify sandbox store. [3](https://shopify.github.io/themekit),[4](https://www.shopify.com/partners/blog/95401862-3-simple-steps-for-setting-up-a-local-shopify-theme-development-environment)

<details>
<summary>Resources</summary>

1. [Creating development stores](https://help.shopify.com/en/partners/dashboard/managing-stores/development-stores)
2. [Bogus Payment Gateway](https://help.shopify.com/en/partners/dashboard/managing-stores/test-orders-in-dev-stores#testing-using-shopifys-bogus-gateway)
3. [Themekit](https://shopify.github.io/themekit/)
4. [3 Simple Steps for Setting Up a Local Shopify Theme Development Environment](https://www.shopify.com/partners/blog/95401862-3-simple-steps-for-setting-up-a-local-shopify-theme-development-environment)
</details>

### Products

1. Know about Product Variants. [1](https://help.shopify.com/en/manual/products/variants), [4](https://www.youtube.com/watch?v=UUIP1n_9kP8)

2. Know about the 100 Variant limit and 3 option limit. [2](https://help.shopify.com/en/manual/products/variants/add-variants#considerations-for-adding-variants)

3. Know what options exist to accomidate the 100 variant limit. [3](https://paulnrogers.com/getting-around-the-shopify-product-variants-limit/)

<details>
<summary>Resources</summary>

1. [Product Variants](https://help.shopify.com/en/manual/products/variants)
2. [Variant limitations](https://help.shopify.com/en/manual/products/variants/add-variants#considerations-for-adding-variants)
3. [Getting Around the Shopify Product Variant Limit](https://paulnrogers.com/getting-around-the-shopify-product-variants-limit/)
4. [How to Add Variants to Products (Video)](https://www.youtube.com/watch?v=UUIP1n_9kP8)
</details>

### Liquid basics

1. Understand the basics of liquid including tags and filters. [1](https://shopify.github.io/liquid/basics/introduction/)

2. Know Shopify's specific objects, tags, and filters. [2](https://shopify.dev/docs/themes/liquid/reference), [3](https://www.christhefreelancer.com/shopify-liquid-guide/)

3. Know of the Shopify liquid cheatsheet. [4](https://www.shopify.com/partners/shopify-cheat-sheet)

4. Know of the Snippets Library. [5](https://shopify.github.io/liquid-code-examples/)

<details>
<summary>Resources</summary>

1. [Liquid Introduction](https://shopify.github.io/liquid/basics/introduction/)
2. [Shopify's Liquid introduction](https://shopify.dev/docs/themes/liquid/reference)
3. [Shopify Liquid The Ultimate Guide](https://www.christhefreelancer.com/shopify-liquid-guide/)
4. [Shopify Liquid Cheatsheet](https://www.shopify.com/partners/shopify-cheat-sheet)
5. [Snippets Library](https://shopify.github.io/liquid-code-examples/)
</details>

### Route object

1. Know the routes object why it's important for multi-lingual stores. [1]

<details>
<summary>Resources</summary>

1. [Routes Object](https://shopify.dev/docs/themes/liquid/reference/objects/routes)
</details>

### Translations

1. Know how to leverage translations keys and the `| t` liquid filter for Shopify translations. [1](https://shopify.dev/tutorials/develop-theme-localization-use-translation-keys)

2. Know how to avoid escaping html through the use of `_html` translation keys. [2](https://shopify.dev/tutorials/develop-theme-localization-use-translation-keys#including-html-in-translation-keys)

3. Know where in the Shopify admin a merchant can directly make translation updates. [3](https://help.shopify.com/en/manual/using-themes/translate-theme)

4. Understand how multi-lingual translations operate. [4](https://help.shopify.com/en/manual/sell-online/multilingual-online-store)

5. Understand how to develop themes to support multi-lingual stores. [5](https://shopify.dev/tutorials/support-multiple-languages-in-apps-and-themes#developing-themes-that-support-multiple-languages)

<details>
<summary>Resources</summary>

1. [Translation keys and the t filter](https://shopify.dev/tutorials/develop-theme-localization-use-translation-keys)
2. [Including HTML in translation keys](https://shopify.dev/tutorials/develop-theme-localization-use-translation-keys#including-html-in-translation-keys)
3. [Translating your store](https://help.shopify.com/en/manual/using-themes/translate-theme)
4. [Multilingual Stores](https://help.shopify.com/en/manual/sell-online/multilingual-online-store)
5. [Developing themes that support multiple languages](https://shopify.dev/tutorials/support-multiple-languages-in-apps-and-themes#developing-themes-that-support-multiple-languages)
</details>

### Alternate Templates

1. Understand how to create and leverage alternative templates. [1](https://shopify.dev/tutorials/customize-theme-create-alternate-templates)

<details>
<summary>Resources</summary>

1. [Create alternate templates](https://shopify.dev/tutorials/customize-theme-create-alternate-templates)
</details>

### Metafields

1. Know what a metafield is. [1](https://help.shopify.com/en/manual/products/metafields/index)

2. Know what the metafield object is. [2](https://shopify.dev/docs/themes/liquid/reference/objects/metafield)

3. Know how to show metafields in the theme. [3](https://help.shopify.com/en/manual/products/metafields/index#show-metafields-in-the-storefront),[4](https://www.shopify.com/partners/blog/110057030-using-metafields-in-your-shopify-theme)

4. Understand when and how to use private metafields. [5](https://shopify.dev/tutorials/store-data-in-metafields#private-metafields)

<details>
<summary>Resources</summary>

1. [Metafields](https://help.shopify.com/en/manual/products/metafields/index)
2. [Metafield object](https://shopify.dev/docs/themes/liquid/reference/objects/metafield)
3. [Show Metafields in the storefront](https://help.shopify.com/en/manual/products/metafields/index#show-metafields-in-the-storefront)
4. [Using Metafields in your Shopify theme](https://www.shopify.com/partners/blog/110057030-using-metafields-in-your-shopify-theme)
5. [Private metafields](https://shopify.dev/tutorials/store-data-in-metafields#private-metafields)
</details>

### Tags

1. Understand creating and using tags. [1](https://help.shopify.com/en/manual/productivity-tools/using-tags)

2. Understand the valid formats of a tag. [2](https://help.shopify.com/en/manual/products/details/tags)

3. Understand the limitations of a tag. Such as a maximum of 250 tags per product.

4. Know how to leverage product tags for collection filtering and the limitations. [3](https://shopify.dev/tutorials/customize-theme-filter-collections-with-product-tags)

<details>
<summary>Resources</summary>

1. [Creating and using Tags](https://help.shopify.com/en/manual/productivity-tools/using-tags)
2. [Tag formats](https://help.shopify.com/en/manual/products/details/tags)
3. [Filter collections with product tags](https://shopify.dev/tutorials/customize-theme-filter-collections-with-product-tags)
</details>

### Metafields vs Tags

1. Understand when to use a Shopify Tag vs a Metafield. [1](https://paulnrogers.com/shopify-tags-vs-metafields/)

<details>
<summary>Resources</summary>

1. [Tags vs Metafields in Shopify and Shopify Plus](https://paulnrogers.com/shopify-tags-vs-metafields/)
</details>

### Line Item Property

1. Understand what a line item property is. [1](https://shopify.dev/docs/themes/liquid/reference/objects/line_item#line_item-properties)

2. Understand how to surface line item properties as custom inputs in a theme. [2](https://ui-elements-generator.myshopify.com/pages/line-item-property)

3. Know how to hide line item properties from the customer in checkout using the `_` prefix. [3](https://community.shopify.com/c/Shopify-Design/Product-pages-Get-customization-information-for-products/m-p/616525#hide-line-item-properties)

<details>
<summary>Resources</summary>

1. [Line Item Property Object](https://shopify.dev/docs/themes/liquid/reference/objects/line_item#line_item-properties)
2. [Line Item Property Input Generator](https://ui-elements-generator.myshopify.com/pages/line-item-property)
3. [Hide Line Item Properties](https://community.shopify.com/c/Shopify-Design/Product-pages-Get-customization-information-for-products/m-p/616525#hide-line-item-properties)
</details>

### Shopify Scripts
1. Understand the basics of Ruby. [1](https://www.codecademy.com/learn/learn-ruby)
2. Understand what Shopify scripts are and how to use them. [2](https://help.shopify.com/en/manual/apps/apps-by-shopify/script-editor/), [3](https://help.shopify.com/en/manual/apps/apps-by-shopify/script-editor/examples)
3. Know the Shopify Scripts API. [4](https://help.shopify.com/en/manual/apps/apps-by-shopify/script-editor/shopify-scripts)
4. Know the limitations of Script such as not being able to add products and lack of API. [5](https://help.shopify.com/en/manual/apps/apps-by-shopify/script-editor/limitations)
5. Know about the unofficial Shopify Scripts generator. [6](https://jgodson.github.io/shopify-script-creator/)

<details>
<summary>Resources</summary>

1. [Learn Ruby Fundamentals](https://www.codecademy.com/learn/learn-ruby)
2. [Shopify Scripts & Script Editor](https://help.shopify.com/en/manual/apps/apps-by-shopify/script-editor/)
3. [Shopify Scripts Examples](https://help.shopify.com/en/manual/apps/apps-by-shopify/script-editor/examples)
4. [Scripts API](https://help.shopify.com/en/manual/apps/apps-by-shopify/script-editor/shopify-scripts)
5. [Limitations of Scripts](https://help.shopify.com/en/manual/apps/apps-by-shopify/script-editor/limitations)
6. [Scripts Generator](https://jgodson.github.io/shopify-script-creator/)
</details>

## App Development

### App types

1. Know the differences between different types of apps (Private vs Unslited vs Public). [1](https://help.shopify.com/en/manual/apps/app-types)

### API versioning & rate limiting 

1. Understand Shopify's API Versioning scheme and quarterly release/deprecation cycle. [1](https://shopify.dev/concepts/about-apis/versioning)
2. Understand how Shopify rate limits the REST and Graphql Admin APIS. [1](https://shopify.dev/concepts/about-apis/rate-limits)
3. Know that Shopify Plus stores have double the rate limits. [1](https://shopify.dev/concepts/about-apis/rate-limits#resource-based-rate-limits)
4. Know that the popular `Shopify-api-node` library respects rate limiting and allows for configuration. [1](https://github.com/MONEI/Shopify-api-node#shopifycalllimits)

### Security best practices

1. Know how to rotate credentials and why it's important. [1](https://shopify.dev/tutorials/rotate-revoke-api-credentials)
2. Know that access tokens should be encrypted at rest. 
3. Know that all API requests should be verified via session before taking actions on behalf of a user.
4. Know that all user input should be cleaned and verified before saving to DB.

### Useful packages

1. [Shopify API Node](https://github.com/MONEI/Shopify-api-node) - #1 package to connect to Shopify's REST API via NodeJS.
2. [Shopify Quilt](https://github.com/Shopify/quilt) - Collection of official Shopify Javascript packages.
3. [Admin-graphql-api-utilities](https://github.com/Shopify/quilt/tree/master/packages/admin-graphql-api-utilities) - Super useful package when interacting with the Storefront and Admin Graphql libraries.
4. [Polaris React](https://github.com/Shopify/polaris-react) - Shopify's official component library to create apps consistent with Shopify's UI/UX.
5. [App-bridge-react](https://www.npmjs.com/package/@shopify/app-bridge-react) - Shopify's library for creating embedded apps that interact with Shopify such as showing modals, alerts, etc.

## Miscellaneous

1. Know about the developer changelog which is where Shopify announces developer facing changes and features. [1](https://shopify.dev/changelog)

<details>
<summary>Resources</summary>

1. [Developer Changelog](https://shopify.dev/changelog)
</details>


