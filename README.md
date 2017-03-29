# office-hours-site

This is the code for the Office Hours site: oh.techatnyu.org

In the _data folder you have a volunteers.csv file. That's pretty much all you need to change if you need to add more volunteers to the site.
The responses for the 'Tech@NYU Office Hours Questionnaire' can be downloaded as a .csv file. For everything to work correctly, you have to open the .csv (that you downloaded from the google form) and then change the header (the first row)
Change:
- 'Name' to 'name'
- 'Email' to 'email'
- 'Website' to 'website'
- 'Currently you are a* (student studying, intern designer, working where as what?)' to 'position' 
- 'You feel comfortable talking to people about*' to 'topics'
- 'Calendly Link' to 'calendly'

So the first row should look like: Timestamp | name | email | website | position | about | topics | calendly
Make sure all links in the responses start with https:// or http:// or else they won't work.

After you make the changes you can do 'git commit -a -m "commit message"' in the terminal and push and you're all set!
