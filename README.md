# Facebook-ADDon

Sheet codes 


Get feed 
=IMPORTFEED("https://gbhackers.com/feed","items url","",1)    


Extract content 

=JOIN(CHAR(10),IMPORTXML(A2,"//div[@class='td-post-content']//p//text()"))


A2=get feed

other formulas 

Formulas 
//div[@class='post-content']/a/@href           for url inside article 
//*[@class="action_url"]/div/h2/a/@href         
//*[@class="post-content"]/div/h2              Heading with tags 
//div[@class="post-content"]/h2/a
