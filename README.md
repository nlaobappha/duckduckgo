# duckduckgo
Write a PyTest module that queries the DuckDuckGo api for “presidents of the united states,” and tests that each president is listed in the response.
(If you need a list or our presidents, see "https://www.whitehouse.gov/about-the-white-house/presidents/")
The presidents should be listed in the RelatedTopics returned field.  RelatedTopics is a list, and you should check the Text entries of RelatedTopics to search for presidents.
We’ll only look for the last name of a president.  That means that we won’t distinguish between John Adams and his son, John Quincy Adams, or George Bush the senior and ‘W.’
Place your test code in a GitHub repository. 
