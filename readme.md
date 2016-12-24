# Read Me

Source of this chart was Nathan Yau's excellent [Jobs Charted by State and Salary.](http://flowingdata.com/2014/07/02/jobs-charted-by-state-and-salary/)

## Visualize and Accelerate Web Site Repairs 

### Focus on the fundamentals with a D3.js interactive treemap

Are you struggling to meet an aggressive deadline for migration to a new video player? Wondering what area of your web site should be targeted next for conversion to responsive design? In web publishing, there are always components in transition from trusted to obsolete. 

When the job to be done is finding and fixing problems that are disrupting web site visits today, or finding and proactively retiring obsolete code that will hinder your site's ability to deliver good experiences in the future, this tool can:

1. Help you visualize where in the site problems are occurring, with their level of severity.
2. Reveal by microsite name and traffic how much this severity should matter to you.

The result is that you can conduct a lightweight cost-benefit analysis, mentally comparing the level of work needed for the repair, on the one hand, to an estimate of the resulting benefit, or lack thereof, of making the repairs, on the other hand, and you can fix the content that's most important to your mission, first, and retire the content that is no longer delivering benefits to save staff time for more important things.

Repair does not need to be spotty or haphazard; instead, proactively understand and prioritize the work that should be done, based on an ecology-wide view where you can think about your MISSION, the problem's severity, and your staff availability.


### Screenshot (this version is NOT interactive)

![Screenshot](https://cloud.githubusercontent.com/assets/10210191/21468551/52f97b3c-c9e5-11e6-81f2-10ad662bb16a.png)

## Recommendations

- Create a database and add a 100-percent content inventory from a web spidering tool or a programmer's tool such as the HTML::Tree module of Perl.
- Aggregate content inventory components to two levels, (1) the top-level category as the people/resource considered to be the content steward or owner, shown here as "topics," and (2) by "communication package" name, also known as microsite or content group - one package for each thematic group of pages you own.
- For each communication package, create a summary strategy statement in the form, "By delivering (information) to (audience) we will be better able to (goal) because (justification)." Source: Bob Boiko, Metatorial Services Inc. (2008). "You want systems but you need strategy." In E. D. Koenig and T. K. Srikantaiah (Eds.), Knowledge Management in Practice: Connections and Context. ASIS&T Monograph Series. Medford, NJ: Information Today, Inc. See also Gothelf, Jeff, and Seident, Josh. (2016). Lean UX: Designing Great Products with Agile Teams, 2nd Ed. Sebastapol, CA: O'Reilly, Declaring assumptions.
- Export traffic in CSV from a traffic tool by month, join / aggregate to communication packages, divide total communication package traffic by the number of months for which data is available. This removes a bias against brand new content; for example, this method is better than comparing 12 months of data for most communication packages to 1 month of data for a communication package added last month. However, this method can provide artificially higher totals for low-traffic packages.
- After you have the inventory and average monthly traffic as the foundation, you can layer on one or more issues of the day - shown here is a common problem, broken link reporting, an easy join in the database.
- Under the chart, add a sortable table as an accessible equivalent.