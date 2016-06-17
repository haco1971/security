# Passive information gathering

It is passive in the meaning that it doesn't directly send packets to the service. But in any other sense of the word there is nothing passive about this phase.


 - Web information
Read through the website. What does it do.

 - Email Harvesting

Find as many emails as possible. Are any of those emails in any pwnable databases?

https://haveibeenpwned.com

 - Whois enumeration

Who is behind the website etc.


## Google hacking
Google is a good tool to learn more about a website.

### Finding specific filetypes
`filetype:pdf`

### Search within webaddress
`site:example.com myword`

### Find in url

`inurl:test.com`

### Wild cards

You can use the asterisk to as a wildcard:
`*`
Example:
`"I've been * for a heart"`
This will return answers where * is anything.

## Exclude words
`-` the dash excludes a specific word

This query searches for pages that used the word bananasplit. 
`-banana bananasplit`

### Cached version
So if a website has been taken down you can still find the cached version, of the last time google visited the site

`cache:website.com`

https://www.blackhat.com/presentations/bh-europe-05/BH_EU_05-Long.pdf


## Examples

Find login-pages on sites that use the ending .bo. For bolivia.
`site:bo inurl:admin.php`


## More
Here are some more

Great guide for google dorks
https://www.blackhat.com/presentations/bh-europe-05/BH_EU_05-Long.pdf

http://www.googleguide.com/advanced_operators_reference.html

http://www.searchcommands.com/

https://support.google.com/websearch/answer/2466433?hl=en
## References
http://www.technicalinfo.net/papers/PassiveInfoPart1.html