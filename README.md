# github_csa : Solution for CSA_Technical_Exercise
Read the ppt 'github_presentation' for the approach on the solution. This github organization and repository are configured as explained below 

# 1) Orgnization configuration
1) create a webhook to subscribe to events that occur in a specific organization
2) Verified webhook from a request catcher for Organization: https://csa_ta.requestcatcher.com/
3) cofigure email notification on the events

# 2) Repository configuration
1) create a webhook to subscribe to events that occur in a specific repository
2) Verify webhook from request catcher for Repository: https://csa_ta.requestcatcher.com/
3) Configure protection ules via bracnh ruleset
4) Enable code security with CodeQL analysis
5) Enable secret scanning
6) Configure email notification

# 3) Automation
1) create workflows with github Actions to trigger on push, pull and branch protection rules creation/modification, 
