---
title: Interview Summary
description: Notes that synthesize findings from all interviews
date: '2020-01-01'
---

## TL;DR

The website is functional enough, though some functions could be improved for the usability of site. Some suggested changes are API based, but some indications of changes in product information would be good. This is consistent with the top dealers who have automated the process of consumers ordering from their site, and as such don't interface very often with the site.

An update to the Murphy's website will need to ensure that product information is prioritized, so dealers who use our Web Services API can easily gather data about products at they go live on their store.

## What Murphy's does well:

The general style and look of the website so far is not a consideration. By most accounts, the website functions well enough. When asked, the average rating of the site from 1-10 was a 7.6, showing that even if the design might seem bad from an end consumer perspective, it is working well for our most profitable dealers. The product selection is good enough to make up for the fact that competitors have a better on-site experience. Translations are super critical to the site operation for dealers abroad and those are handled decently well. The shipping overview is super helpful for dealers, could potentially be more accessible?

Updating the aesthetic of the website seems that it will be a mostly consumer-facing endeavor. However, presenting an effectively planned informational architechture will ensure that dealers can get on our site, get the information they need for upcoming sales and make their operations more easy to perform.

## What Murphy's does wrong:

Information in regards to products disappears or changes without warning, requiring that process to be handled manually. This normally isn't a problem but with the volume of new products put out by Murphy's, it can be harder to manage. This is an API problem, and not so much a problem with the design of the site itself. There are a multitude of API changes that will make the ease of use better for customers that could be implemented, all within a range of difficulty from relatively basic to necessitating a fundamental shift in the way that Web Services runs. These concerns aren't important to the immediate design of our website but compose the overwhelming majority of issues reported by dealers.

Searches and general site navigation is slow, detrimental to the overall user experience. Search strictness requires near perfect accuracy to ensure that your search actually works, which can be problematic if English is a secondary language or your typing isn't 100% accurate all of the time.

The Account Page has so many options that were just regarded as "interesting but not something they have ever used". While no one attributed the features as a negative, the majority of users expressed a lack of need for the overwhelming number of links that were in their account page.


## Notable aspects of the site that aren't critical but good to know:

- Use cases for pages in the "My Account" vary significantly depending on dealer and location. 
- Back in Stock Items and New Magic are accessible without the `<nav>` on the homepage. Worth seeing how to rearrange those elements to make them even more obvious.
- The majority of top dealers use Web Services to automatically order items on demand, very few order items in advance of a customer purchase
- Web services trivializes all but the essential services on our page because orders are done on demand through our automated services.

## What we need to fix:

The way that products, prices, image, and code changes needs to give a clear indication that changes are happening. This change needs to be something that happens on the website as well as through the API. Searches are slow to load and require exact input to find the right result.

Changes made to the overall UX of the site will need to maintain a mental model that closely resembles the current site, or ensure at the very least that it doesn't deviate too radically.