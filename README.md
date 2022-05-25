# phuckphishers
Let's fight the spammers that attempt to phish for personal information.


## Helpful Links
Join the fight against phishing with Cisco Talos: https://www.phishtank.com

How to preview shortened urls: https://security.thejoshmeister.com/2009/04/how-to-preview-shortened-urls-tinyurl.html

We will be leveraging this list: http://www.tipsandscripts.net/2017/03/links-to-report-abuse.html?view=classic

## The Plan
Make it easy to report phishing and spam directly to the owners of the tools used by spammers:
- user gets spam on Gmail
- user selects the more button
- from the more list user selects show original
- user presses the copy to clipboard button
- user runs the phuckphishers application
- user pastes the email into a text box in the phuckphishers application
- the phuckphishers application scans the email for links
- for each url in the list phuckphisher determines if there is an abuse reporting option
-- where possible abuse reporting is done automatically
-- where not possible the user is advised on what actions to take
