# Read Me

## Visualize and Accelerate Web Site Repairs - D3.js treemap from JSON

> My car's dashboard has an indicator that tells me when it's time for an oil change and tune-up - it flashes **Maintenance Required**. My organization's web content management system has nothing similar; that's what this is for.


### Focus on the big picture and improve your web site quality

This HTML, D3.js treemap with JSON data allows you to "focus on the big picture," visualizing and interacting with web content-audit reporting, such as (this example) broken link reports by org chart piece/content owner/line of business, web product name, severity, and traffic level, using a D3.js version 7+ treemap. Overview first, zoom and filter, details on demand.

This is a rewrite of Nathan Yau's "Jobs Charted by State and Salary," https://flowingdata.com/2014/07/02/jobs-charted-by-state-and-salary/.

Put your own content-audit data into this JSON format and you will have:
- A treemap grouped by "line of business" / content steward (parent nodes) and page group / product name (leaf nodes).
- Click a blue-shaded (problems found) box to load the drill-down report.
- Box volume = 1 of 3 selected “volume” metrics (dropdown; default is product page count).
- Fill shading, i.e., box background = broken-link severity for the product (issue_instances); gray means no errors found; blue means errors found, with darker blue meaning more errors. White means no traffic to the product in the time period studied.
- Highlights on/off = traffic cutoff: Move the traffic slider to focus on what might be your highest customer harm, meaning, areas where the highest number of customers are encountering broken links.

