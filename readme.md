# Read Me

Source of this chart was Nathan Yau's [Jobs Charted by State and Salary.](http://flowingdata.com/2014/07/02/jobs-charted-by-state-and-salary/)

## Visualize and Accelerate Web Site Repairs 

> My car's dashboard has an indicator that tells me when it's time for an oil change and tune-up - it flashes **Maintenance Required**. My organization's web content management system has nothing similar; that's what this is for.


###Focus on the big picture and improve your web site quality. D3.js treemap from JSON

Have you felt blindsided by a new requirement for web site repair? How bad is it? Or, are you struggling to meet an aggressive deadline for migration to a new video player? Wondering what area of your web site should be targeted next for conversion to responsive design? What is the scope of the work you need to do? In what sequence should this new work be one? In web publishing, there are always components that are in transition, moving from "trusted" to "obsolete." Do you know where they are? How much damage are they causing right now to your user experience? What do you plan to do about them?

When the job to be done is finding and fixing problems that are disrupting web site visits today, or finding and proactively retiring obsolete code that will hinder your site's ability to deliver good experiences in the future, this tool can:

1. Help you visualize where in the site problems are occurring, with their level of severity.
2. Reveal by microsite name and traffic how much this severity ought to matter to you as you plan your repairs.

This is done by establishing a foundational metaphor for your whole ecology - a map of the territory. Then when any new issue arises, you overlay the new report, consisting of URL-Problem Description, quickly and easily onto the map so all teams can see and understand where they stand in regard to this new maintenance problem.

The result is that team members can conduct a lightweight cost-benefit analysis for every microsite they own, mentally comparing the **cost** of repairing the content, on the one hand, to an estimate of the resulting **benefit**, or lack thereof, of investing resources in repairs, on the other hand. Then they can work out fixing the content that's most important to the organizational mission, FIRST, and you can retire content that is no longer delivering benefits, which will free up staff time to improve the web communications that offer better return on your staff investment.

Repair does not need to be spotty or haphazard; instead, proactively UNDERSTAND and PRIORITIZE the work that should be done, based on an ecology-wide view where you can think about your MISSION, the problem's severity, your staff availability, etc.


### Screenshot (this version is NOT interactive)

Rectangle volume shows relative number of HTML pages; some communication packages are small; some are large. Green shading means no errors were found. Shade of red shows severity of the problem being analyzed. In this version of the map, points are used, so management can increase the severity of a particular problem the organization wants solved before others. For example, here the broken link counts are multiplied by two in order to be more prominent among all possible problems analyzed.

![Screenshot](https://cloud.githubusercontent.com/assets/10210191/21468551/52f97b3c-c9e5-11e6-81f2-10ad662bb16a.png)

## Recommendations

- Create a database and add a 100-percent content inventory from a web spidering tool or a programmer's tool such as the HTML::Tree module of Perl.
- Aggregate content inventory components to two levels, (1) the top-level category as the people/resource considered to be the content steward or owner, shown here as "topics," and (2) by "communication package" name, also known as microsite or content group - one package for each thematic group of pages you own.
- For each communication package, create a summary strategy statement in the form, "By delivering (information) to (audience) we will be better able to (goal) because (justification)." Source: Bob Boiko, Metatorial Services Inc. (2008). "You want systems but you need strategy." In E. D. Koenig and T. K. Srikantaiah (Eds.), Knowledge Management in Practice: Connections and Context. ASIS&T Monograph Series. Medford, NJ: Information Today, Inc. See also Gothelf, Jeff, and Seident, Josh. (2016). Lean UX: Designing Great Products with Agile Teams, 2nd Ed. Sebastapol, CA: O'Reilly, Declaring assumptions.
- Export traffic in CSV from a traffic tool by month, join / aggregate to communication packages, divide total communication package traffic by the number of months for which data is available. This removes a bias against brand new content; for example, this method is better than comparing 12 months of data for most communication packages to 1 month of data for a communication package added last month. However, this method can provide artificially higher totals for low-traffic packages.
- After you have the inventory and average monthly traffic as the foundation, you can layer on one or more issues of the day - shown here is a common problem, broken link reporting, an easy join in the database.
- Currently, clicking a rectangle takes the user to a blank database report page. Use this to provide the list of individual pages to repair.
- Under the chart, add a sortable table as an accessible equivalent.