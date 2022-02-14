---
title: Interview Conclusions
description: Notes that synthesize findings from all 15 interviews
date: '2022-01-31'  
---

## Interview Findings:

*Our initial hypothesis of the most important user flow were wrong. Most dealers only access the site to perform administrative tasks and depend on product data from us since most everything else is automated. User searches are important, but the priorities in the redesign should lie in granting dealers more assets, product information, and streamlining the data they do see on a regular basis. This suggests an approach that minimizes friction and increases speed will be the best upsell strategy. Downloads are a potential area of growth that needs a redesign to see its fullest potential.*

The website is functional enough according to dealers (our current target audience), though some functions could be improved for the usability of the site. The most necessary design change from a UI (User interface) perspective would be a mobile friendly rework that retains most of the elements that make the website successful. This isn't backed by their data as much as a need to follow updated SEO guidelines. Most dealers like the site as it is right now so care must be taken to ensure that we retain those mental models in the site UX while providing them something they didn't know they needed.

An update to the Murphy's website will need to ensure that product information is prioritized, so dealers who use our Web Services can easily gather data about products as they go live on their stores, as well as those who don't. *One especially important area of improvement involves the omission of upcoming presales from viewing on the site, where dealers must find our emails or remember the latest magic news to order products.* Our initial assessments of product searches from analyzing the site map and using Analytics appears to be incorrect as a result of these findings. 

## Interview Trends, Quantified:
- 8/13* dealers interviewed mentioned using a combination of *New Products, Coming Soon, or Back in Stock* as a regular part of their workflow.
- 3/13* dealers ordered products using a manual process, though all of them stated a desire to automate more parts of their business.
- Downloads were a common sore spot with 4/15 interviews discussing critical user issues that lost them business or prevented them from implementing downloads.
- Only 2/15 dealers stated that they used a mobile device. Uncommon but still used.
- Over 4 dealers mentioned their need for assets and faster access to product information to inform consumers, advertise products, and learn about discontinued items.
 
`* The sample size here is comparatively smaller to account for 2 of the subjects interviewed were developers and not dealers.`

## Critical findings:

- **Our initial assumptions about who dealers are and how they use the website does not match how dealers use our website.** The predicted user flow of searching was not common at all, and almost all dealers use our generated lists to find products. This assessment is slightly top heavy though.
- Once more, user interface design isn't the priority. **Streamlining the information gathering process is, however.**
- Due to the large volume of products we carry, users are incentivized to use our Web Services to automate the process of choosing what items appear on their site. Manual operations of the site are usually to get more data for products or conducting bookkeeping. 
- If Dealers don't use web services, they desire automation but often lack the financial resources or technical know-how to achieve this.
- Downloads were not the most common complaint but the severity makes them important to address. Businesses wish to implement downloads but struggle with how Murphy's has implemented them for both *financial and UX reasons.* These last two points hint at a need to improve dealer onboarding.

## What Murphy's does well:

The general style and look of the website so far is not a consideration. By most accounts, the website functions well enough and is well liked by the dealers. Even if the design might seem difficult to use from an end consumer perspective, it is working well for the majority of dealers regardless of the business size. The product selection makes up for the fact that some competitors have a better on-site experience, though we're not far off from them if at all. This tracks with the UX of wholesale websites, with a notorious track record for poor UI/UX. Translations are super critical to the site operation for dealers abroad and those are handled decently well. The shipping overview is super helpful for dealers, could potentially be more accessible?

Updating the aesthetic of the website seems that it will be a mostly consumer-facing endeavor. However, presenting an effectively planned informational architecture will ensure that dealers can get the information they need for upcoming sales and make their operations more easy to perform. 
## What Murphy's does wrong:

Information in regards to products disappears or changes without warning, requiring that process to be handled manually. There are a multitude of API changes that will make the ease of use better for customers that could be implemented, all within a range of difficulty from relatively basic to necessitating a fundamental shift in the way that Web Services runs. These concerns aren't important to the immediate design of our website but compose the overwhelming majority of issues reported by dealers.

Searches and general site navigation is slow, detrimental to the overall user experience. Search strictness requires near perfect accuracy to ensure that your search actually works, which can be problematic if English is a secondary language or your typing isn't 100% accurate all of the time.

The Account Page has so many options that were just regarded as "interesting but not something they have ever used". While no one attributed the features as a negative, the majority of users expressed a lack of need for the overwhelming number of links that were in their account page.

Downloads are so difficult for a site to implement that they impede sales from a number of dealers and are a constant headache for those who have successfully done it. Currency restrictions prevent their implementation in Japan, the method of invoicing downloads makes recording payments difficult, and the process for consumers to access content is riddled with unnecessary difficulty in terms of getting sales out of end consumers.


## Notable user behaviors:

- Use cases for pages in the "My Account" vary significantly depending on dealer and location. 
- Back in Stock Items and New Magic are accessible and most often used without the `<nav>` on the homepage. Worth seeing how to rearrange those elements to make them even more obvious, since the majority of those inquired did not use the navbar to find their way through the site.
- The majority of top dealers use Web Services to automatically order items on demand, very few order items in advance of a customer purchase and spend minimal time on our website as a result. Their use patterns coincide with a need for information in order to deliver it to customers to address customer support or promotional needs.
- Web services trivializes all but the essential services on our page because orders are done on demand through our automated services.

## Suggested Improvements:

- The way that products, prices, image, and code changes needs to give a clear indication that changes are happening. This change needs to be something that happens on the website as well as through the API. Searches are slow to load and require exact input to find the right result.

- Changes made to the overall UX of the site will need to maintain a mental model that closely resembles the current site, or ensure at the very least that it doesn't deviate too radically.

- Downloads will need to be fixed from the bottom up, and might be a stretch goal where the product page works as it does today but will eventually work with a feature set more conducive for dealers to sell videos on their site.

- Upsell will revolve around providing information to dealers in the most efficient way possible. There's potential to resell old magic tricks with a new coat of paint/tutorials for minimal cost.

- The accounts page needs to be streamlined to make the UI easier to navigate, removing outdated menus cross-checked with analytics.