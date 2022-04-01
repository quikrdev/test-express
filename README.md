Quikr Javascript Node Express



Welcome to the test...
Please clone the repository.

You can execute a GET against the following endpoint, https://api.quikr.co.za/testdrive/distance, to determine the driving distance between 2 addresses. Below is a json sample of the body that can be used.
{   "fromAddress":"8 Boundary Rd, Rondebosch, Cape Town, 7700",    "toAddress": "Fritz Sonnenberg Rd, Green Point, Cape Town, 8051"}

With the directory hierarchy below in mind...
-> src     -> controllers     -> models     -> routes     -> views

Setup an express server on port 8081.

Create a route ...routing/optimise

The route will need to call a function to optimise routing for a series of addresses from a starting point
This is some sample json {    "start":"263 Victoria Rd, Salt River, Cape Town, 7925",    "drops": [       "10 Navarre Cres, Belhar 13, Cape Town, 7493",       "10 Oranje St, Ruyterwacht, Cape Town, 7460",       "6 Keurboom Rd, Thornton, Cape Town, 7460",       "10 Glebe Rd, Rondebosch, Cape Town, 7700",       "40 Koodoo St, Kewtown, Cape Town, 7764",       "120 Norwood Ave, Avonwood, Cape Town, 7490"    ] }

When the closest address to 263 Victoria is found, it should be the starting point for the next drop.Can you visually display the starting point and drops ?
Consider using synchronous execution and how you would write the optimised route to a data table.
Please make a Pull Request to submit your code for review.

Good luck.
