# cometitors-with-account
Competitor app with Accounts


# Competitors App
<a href="https://githubsfdeploy.herokuapp.com?owner=meighan&repo=competitors-with-account">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/src/main/webapp/resources/img/deploy.png">
</a>


## Overview
This app is used to hold competititive intelligence in Salesforce for sales enablement on a custom Record Type of the Account object that is then linked to Opportunity Records.  Also gives better reporting than the horror that is multiselect picklists for Competitors on Opportunities.  You can see who you compete against, when you win, and when you lose, and why, so you can determine if it is a feature, poor sales content, or a training issue.

### Details
Includes 2 Custom Objects, "Competitors" to hold Competitor data, and "Opportunity Competitors", a junction object between Accounts with the Record Type Competitor and Opportunities with custom insight from the sales team about being head to head with the competitor in that deal.  2 Lightning App builder pages are customized and applied to the opp page for the competitor info to be easily accesse without having the click to the competitor.

### After install
Once installed update your page layouts as you see fit and add any additonal info your sales team needs to the accounts.Also ensure you add the actions to "Add Competitor" to the Opportunity then Viola!
