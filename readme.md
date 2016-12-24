# Read Me

## Visualize and Accelerate Web Site Repairs 

### Focus on the fundamentals with a D3.js interactive treemap

Are you struggling to meet an aggressive deadline for migration to a new video player? Wondering what area of your web site should be targeted next for conversion to responsive design? In web publishing, there are always components in transition from trusted to obsolete. 

When the job to be done is finding and fixing problems that are disrupting web site visits today, or finding and proactively retiring obsolete code that will hinder your site's ability to deliver good experiences in the future, this tool can:

1. Reveal where in the site problems are occurring, with their level of severity.
2. Reveal by microsite name and traffic how much this severity should matter to you.

The result is that you can conduct a lightweight cost-benefit analysis, mentally comparing the level of work needed for the repair, on the one hand, to an estimate of the resulting benefit, or lack thereof, of making the repairs, on the other hand, and you can fix the content that's most important to your mission, first, and retire the content that is no longer delivering benefits to save staff time for more important things.

Repair does not need to be spotty or haphazard; instead, proactively understand and prioritize the work that should be done, based on an ecology-wide view where you can think about your MISSION, the problem's severity, and your staff availability.


## Screenshot (this version is NOT interactive)

![Screenshot](https://cloud.githubusercontent.com/assets/10210191/21468418/8c07f230-c9dd-11e6-8a0e-3705896620c4.png)

## Recommendations

- Start with a foundation of a 100-percent content inventory and average monthly traffic, in a database. (Average monthly traffic: export from traffic tool by month and divide the total by the number of months for which data is available; this removes a bias against brand new content - don't compare 12 months of data to 1 month of data.)  Use a web spidering tool or a programmer's tool such as the HTML::Tree module of Perl for the content inventory, and CSV exports from your traffic tool.
- With this in the database you can then layer one or more issues of the day - shown here is a common problem, broken link reporting, an easy join in the database.
- Set the top-level category as the people/resource considered to be the content steward or owner. Shown here as "topics." Store the data in hierarchical JSON and display the treemap both as the full site and by content steward.