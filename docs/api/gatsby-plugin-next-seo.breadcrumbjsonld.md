<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [gatsby-plugin-next-seo](./gatsby-plugin-next-seo.md) &gt; [BreadcrumbJsonLd](./gatsby-plugin-next-seo.breadcrumbjsonld.md)

## BreadcrumbJsonLd variable

A breadcrumb trail on a page indicates the page's position in the site hierarchy. A user can navigate all the way up in the site hierarchy, one level at a time, by starting from the last breadcrumb in the breadcrumb trail.

<b>Signature:</b>

```typescript
BreadcrumbJsonLd: FC<BreadcrumbJsonLdProps>
```

## Remarks

BreadCrumbJsonLd creates a [BreadcrumbList](https://schema.org/BreadcrumbList) container item that holds all elements in the list.

```jsx
import React from 'react';
import { BreadcrumbJsonLd } from 'gatsby-plugin-next-seo';

export default () => (
  <>
   <h1>Breadcrumb JSON-LD</h1>
   <BreadcrumbJsonLd
     itemListElements={[
       {
         position: 1,
         name: 'Books',
         item: 'https://example.com/books',
       },
       {
         position: 2,
         name: 'Authors',
         item: 'https://example.com/books/authors',
       },
       {
         position: 3,
         name: 'Ann Leckie',
         item: 'https://example.com/books/authors/annleckie',
       },
       {
         position: 4,
         name: 'Ancillary Justice',
         item: 'https://example.com/books/authors/ancillaryjustice',
       },
     ]}
    />
  </>
);

```
\*
