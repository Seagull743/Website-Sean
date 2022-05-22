# Website Sean


## Website description
This website is created for viewers to get to know me and see work I have previously done. There is also a contact me page, where the viewer can full out a form which sends me an email. 

## Testing/Findings 

* My first problem I had was with css. I noticed when testing my first page that my external css wasn't being registered. Only internal and inline styles were working. Through alot of googling and trial and error, I noticed that I used the src tag when trying to link my stylesheet instead of href.

* Responsiveness was another problem I had with a few of my html pages. When creating my website I was using bootstrap, bootstrap classes have alot of predefined styles e.g padding and margin. From removing inline styles and creating classes, I found out that It was a predefined bootstap class which was stuffing up the page allowing the viewer to scroll left and right. 

* originally I was styling bootstrap classes internally, they had to be internal because external wasn't working. From discussion I found out that it's bad to override bootstrap classes and should only be done if absolutely necessary. To resolve this I cut the styles from bootstrap classes to my own created classes. I then had to put my link to my external css after bootstrap, so that my styles would be prioritised instead of the bootstrap styles.   


## Sources used
[Bootstrap] (https://getbootstrap.com/docs/5.2/getting-started/introduction/ "Bootstrap docs")
[w3schools] (https://www.w3schools.com/ "w3schools home")

