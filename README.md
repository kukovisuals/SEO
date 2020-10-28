# Overview of SEO 

From the book of SEO Management. I'm creating a summary of the book with its important concepts and best practice for SEO.

The folders go in order of the chapters and some images are included from the book :) 

# 1. State of the Art SEO (Search Engines) 

– in Russia, there is Yandex, which has a fairly large market share with more than 50%, while Google has less than 45%;

– in South Korea, there is Naver, which has a market share of 25–30% (Google possesses the majority);

– in Japan, there is Yahoo! Japan, a local search engine based on Bing’s results in Japanese and which has an average market share of about 30%, depending on the year (Google also has the remaining share of the majority in this case).

# 2. Project Management 

To set up SEO campaigns you need to plan:

- Technical optimization;

- Semantic Optimization;

- Optimization of external links (off-site SEO)

- Plans for redirection, website cleaning, etc...

- The writing of fresh and quality content 

- Meetings and call to ensure the smooth running of the project

---------------------------------------------------------------------

For any SEO project, we have specification that list these major steps and 
what we must achieve within them:

- SEO audit (technical and semantic)

- Optimization of external links (off-site SEO) 

- Plans for redirection, website cleaning etc

- The writing of fresh and quality content 

- follow-up

- strategic monitoring

- monitoring e-reputation

----------------------------------------------------------------------

## 2.2 Kick-off meeting 

– monthly SEO positions;
– unique monthly visits;
– number of page views;
– backlinks;
– remaining 4xx error pages;
– remaining 3xx pages (to be removed);
– bounce rate;
– orphaned/poorly linked pages if necessary;
– page indexing rate (number of real pages in the site versus the number of pages indexed by Google);
– active page rate (i.e. pages that have received at least one SEO visit per month);
– inactive page rate (i.e. pages that have not received any SEO visits per month);
– monthly conversions;
– monthly transactions;
– other KPIs that customers can request on demand


## 2.3 Reverse Schedule 

Used in project management, the Gantt chart is one of the most concrete tools for visually representing the progress of the various activities (tasks) that constitute a project. Often, the left column of the diagram lists all the tasks to be performed and the header line represents the most appropriate time units (or dates) for the project (days, weeks, months, etc.). 

## 2.7 The Study of Keywords

To choose the keywords, we must ask ourselves the following questions:

	– Has this word been searched for enough?
	– Is this word too competitive?
	– Does this word match the theme of my page?
	– Who positions themselves with regard to this word? (See competitors in search results.)
	Keywords are part of SEO’s semantic strategy. They are very important to define and target the way a site wants to communicate and position itself.

	The study of keywords is also an essential step in an SEO strategy, because it allows you to:

	– be aware of how Internet users talk about a theme;
	– understand the expectations of Internet users with regard to a subject;
	– optimize the website with popular keywords;
	– position yourself around sought-after and specific requests for which you want to be a specialist in your niche.

## 2.12 Follow-up Maintenance and reporting 

Start monitoring the evolution of the site via KPIs 

	– monthly SEO positions;
	– unique monthly visits;
	– number of page views;
	– backlinks;
	– remaining 404 error pages;
	– remaining 3xx pages (to be removed);
	– bounce rate;
	– monthly conversions;
	– monthly turnover;
	– page indexing rate (number of real pages in the site versus the number of pages indexed by search engines).
	Traffic performance measurement tools exist for each search engine. Here are the best known, which we use regularly:

	– Google Analytics (American);
	– Baidu Tongji (Chinese);
	– Yandex Metrica (Russian).

SEMrush for tracking the keywords on which a site is ranked by default 

tools for SEO ranking:

	– Advanced Web Ranking;
	– SEO Power Suite;
	– Ahrefs Rank Tracker;
	– Myposeo;
	– Ranxplorer;
	– Monitorank;
	– PRORankTracker.


# 3. Technical SEO

Technial SEO: from HTML tags to URL

The technical aspect of SEO takes place in several steps and consists of checking the following points:

– the crawl of the site;
– indexing of web pages;
– the loading time of the pages;
– the internal linking;
– the structure of the site (not too deep).


## 3.2 Compliant URL for SEO 

A URL is considered "non-compliant" when it does not meet the following criteria:

- Precense of an HTML page 
- presence of an HTTP 200 header
- presence of a canonical tag pointing towards itself 
- absence of meta noindex tags in strategic pages 


## 3.9 Loaidng times by page type

To measure and analyze page loading times, we divide a site by page type:

– home page;
– category pages;
– sub-category pages;
– product or article pages.

TOOLS!!! -> such as Dareboost or Web Page Test

What is a good speed index? A good speed index (on mobile) is below 3,000. Here is what the score ranges mean:

– very good: less than 2,000;
– good: less than 3,000;
– fair: less than 5,000;
– bad: between 5,000 and 10,000;
– very bad: more than 10,000.




## 3.10 robots.txt

Here is the syntax proposed by Google (also valid for other search engines) in its online documentation2:

– the robots.txt file must be an ASCII or UTF-8 text file. No other characters are allowed;
– a robots.txt file consists of one or more rules;
– each rule is composed of several directives (instructions) and only one directive per line is required.
A rule provides the following information:

– the robot (user-agent) to which the rule applies;
– the directories or files which this agent can access, if applicable;
– the directories or files which this agent cannot access, if applicable;
– rules are treated from top to bottom and the same user-agent can only fall under one rule, defined as the first most specific rule governing his behavior;
– the starting principle is that from the moment a page or directory is not blocked by a disallow rule, the user-agent can explore it;
– the rules are case sensitive


## Example 1: Only block Googlebot

User-agent: Googlebot

Disallow: /

## Example 2: Block Googlebot and Adsbot

User-agent: Googlebot

User-agent: AdsBot-Google

Disallow: /

## Example 3: Block all bots

User-agent: *

Disallow: /



## 3.11 Sitemap.xml

The sitemap.xml helps to index a site faster. We recommend the following hierarchy to prioritize (in the <priority> tags of a sitemap) the indexing of pages in a site:

– home page: 1.0;
– category pages: 0.8;
– main product pages, bestsellers: 0.8;
– other product pages (ranges, secondary, etc.) : 0.7;
– other pages (company history, team, etc.): 0.5;
– legal pages (legal notices, terms and conditions, etc.): 0.2.


We also recommend having the tag <changefreq> for the frequency of page changes and to indicate the following elements for the types of pages concerned:

– home page: daily;
– news pages (blog, magazine, news, etc.): daily;
– category pages: weekly;
– product pages: daily;
– legal notices, terms and conditions, etc.: monthly.

## 3.17 Meta Tags

The meta tags are composed of the tag <title> and the tag <meta name=“description”>, as well as the tag <meta name=“keywords”>, which would still be effective with an impact on semantic SEO for most Asian engines

These tags must be coded in teh <head></head> part of the tag of the page 

## 3.17 Headings Tags

– H1: level 1 containing the subject or main information 

- H2: Level 2 containning a subtitle of H1

- H3: level 3 Specific to the page and gives more info than H1 and H2

- H4: level 4 containing small titles for each paragraph. Minimal SEO impact 

- H5: level 5 specific product or element name. no impact in SEO 

- H6: level 6 rarely use 


## 3.19 Hreflang Taging

If an owner has a site with several language versions, it is necessary to put the tag <link rel=“alternate” href=“example.com/language-folder/” hreflang=“language-country”/> in the <head> part of the multilingual web pages.


In addition, it is also possible to implement the tag <link rel=“alternate” href=“http://example.com/” hreflang=“x-default”/> to define a default language, which Google will determine as the best for the user if no page seems to be qualified for the user.



## 3.20 Alt attribute tagging 

In concrete terms, alt attributes are found in the image tags and are presented in the form as follows:

<img src=“name.jpg” alt= “Keywords - Product name / Category -Brand”/>

## 3.21 Rich snippets tagging 

Schema.org tags are metadata tags that allow you to add additional info to a webpage. 


## 3.26 Seasonality of Pages 

	1. disentangle the seasonal pages after the period concerned, bt changing titles and meta desription 

	2. remove products when the event has passed but leave the network page on the site (changing category if necessary)


# 4. Semantic SEO, Editorial and Copywriting

## 4.1 Optimization of the title tag

The <title> tag is the tag that would have the most influence in terms of the impact of SEO. This is the title of the search result extract that you see in the search engines.

Characters for the titles (including spaces) in search engine:

- Google: 50
- Baidu: 20
- Naver: 15
- Yandex: 60
- Yahoo! japan: 15 to 20 

Title formats recommendations 

- Home page: Brand | keyword | Category or product names;
- categories page: Category name | keyword | brand;
- product page: Product name | keyword | brand;
- written article pages:  Title of the artcile | keyword | brand;


## 4.2 Optimization of the meta Description 

The tag <meta name=“description” content=“...”> is the tag that allows us to add a description of a sentence in the attribute “content” in order to introduce the elements that Internet users can read in the web page.

limit of the description in characters including spaces 

- Google: 156 
- Baidu: 80 to 100
- Naver: 40 to 45
- Yandex: 155 to 160
- Yahoo! Japan: 45 to 50

By page typology this are some recommendations:

– home page: discover the world of BRAND, specialist in KEYWORD 1, KEYWORD 2. Visit our 	official website EXAMPLE.COM;

– categories page: discover our ranges of CATEGORY NAMES or COLLECTIONS. Visit our 				official website to learn more about the BRAND, specialist in KEYWORD 1, KEYWORD 2 (		possibly);

– product page: discover our product PRODUCT NAME, specializing in KEYWORD 1, KEYWORD 2. 	 Visit our official website EXAMPLE.COM;

– articles page: discover our new article: TITLE OF THE ARTICLE. Visit our official website EXAMPLE.COM.


## Optimization of text content 

websites that contain nearly 2,000 words are rank 1,2 

 - H1: large general topic;
 – H2: major theme;
 – H3: category;
 – H4: subcategory;
 – H5: product;
 – H6: particularities of a product, element or concept;


## Optimization of internal Network size 

The more links the home page has the more likely it is to be well position in search engines 


## Optimization of alt attributes in images 

it is important to put keywords in this images so search engines can display them correctly 

The alt attribute recommended is:

PRODUCT NAME - SEARCHED KEYWORD (from a study of keywords) - Brand


## Optimization of breadcurmbs (anchors)

For users to understand where they are between a site

Here is an ideal breadcrumb according to our recommendations:

Home > Category (search keyword) > Subcategory (search keyword) > Product (with keyword)


# 5. Link Building Methods












