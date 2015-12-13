# Math.mx

Math.mx (mathematics) is a zoomable d3 treegraph of hierarchical mathematical topics (a navigatable taxonomy of math). It's goal is to give one a holistic mechanism for exploring all of math, to learn what they don't know, to discover and see how fields are related, and to contribute/associate resources to help others better undestand each topic.

- Here's my [1st announcement of math.mx on facebook + goals](https://www.facebook.com/michael.karpeles/posts/10102140608410450)
- Here's an [idea + complimentary initiatives](https://www.facebook.com/michael.karpeles/posts/10102182038234750) you may want to explore

## Goals

- **Wiki Data Support:** Resolve every math topic to a wikidata ID
- **Entity Resolve w/ Wikipedia:** Extend the math.mx DAG (which is from the [AMS MSC2010 taxonomy](http://www.ams.org/msc/pdfs/classifications2010.pdf) -- [query it here](http://www.ams.org/msc/msc2010.html?t=92B20&btn=Since+1999)) with https://en.wikipedia.org/wiki/Category:Fields_of_mathematics (iterate over [wikipedia math categories](http://www.mediawiki.org/wiki/API:Categorymembers))
- **Allow Users to Edit:** CRUD (create, read, update, delete) (i.e. back with a database, like s3)
  - Allow each box/cell to be annotated with users' resources (academic papers, videos)
  - Allow users to add children or neighbors to a specific cell
- **Improve Granularity:** Make root nodes in the graph not be "domains", but be so granular they resolve to specific formula.
- **Curricula Generation:** From any given box/cell, allow the user to click a link which generates a (shortest path, ordered) list of dependencies (walks the graph) to learn/understand the selected formula or topic
- **User accounts:**
  - Visualize your comprehension: imagine if each cell in math.mx was colored with a shade of red showing users w/ accounts how well they comprehend a cell (and all its dependencies).

## Links as reference

- http://mathworld.wolfram.com/letters/
- http://www.math.niu.edu/~rusin/known-math/index/
- https://www.khanacademy.org/exercisedashboard
- http://jeffbaumes.github.io/standards/#
- https://dl.dropboxusercontent.com/u/11459286/ccssmgraph.pdf
- http://meta.math.stackexchange.com/questions/6479/a-graph-map-of-math-se
- http://forums.xkcd.com/download/file.php?id=29015&sid=8ae1604e5e548bed844ae0f1275bad43&mode=view
- http://www.aaamath.com/grade6.htm#topic1 - elementary
- https://github.com/stared/tag-graph-map-of-stackexchange
- http://www-old.newton.ac.uk/preprints/NI12010.pdf

## Related Projects

Insofar as interesting data sets go, you may also be interested in https://michaelkarpeles.com/curations/the-foundation (which I hope becomes like the future math.mx described above)
