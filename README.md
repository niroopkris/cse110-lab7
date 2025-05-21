## README
No partner, just me: Niroop Krishnakumar

_Check your understanding_

1. Within a Github action that runs whenever code is pushed. This ensures code is added incrementally and only accepted if it passes our automated tests. Choice 2 is decent but defeats the purpose of automation with Github. Choice 3 is simply bad practice.
2. No
3. Navigation mode loads the page and only then analyzes it, unlike snapshot mode which analyzes the page in its current state without reloading. Navigation mode provides an overall performance metric while snapshot mode is best for finding accessibility issues, as it's quicker and not as thorough when checking other aspects. Snapshot mode also does not measure javascript performance at all unlike navigation mode.
4. First, we could give the <html> element a [lang] attribute as not doing so impacts screen-readers and can make things difficult for blind users that use them. Second, for best practices, it might be good to have a <meta name="viewport"> tag to optimize the page for mobile screens (this also apparently "prevents a 300 millisecond delay to user input"). Third, all the images can be further optimized by reducing their dimensions to be the dimensions which they are actually displayed at. The Largest Contentful Paint element also seems randomly "bigger" (well, only like 150 KiB bigger) than the rest. Considering this is probably a miniscule thing and is only listed as an "issue" on my chrome browser and not PageSpeed Insights, an alternative #3 change would be to add a <meta name=description> element to the document to improve search engine optimization and make the page "appear more relevant."






