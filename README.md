### layout-test

##### Option 1: use Materialize tabs to hold the divs 
##### Pros: Will save time
##### Cons: This may not be a scalable approach; what happens after the div appears? How will the user move to the next section after clicking that div??? I see the mark up getting ridiculously complex as the app grows

##### Option 2: Create two divs by hand; build out each display that will show; use jQuery show hide as the user navigates between views 
##### Pros: Should be able to handle scaling very well, will be able to keep mark up very modular and just use jQuery show hide depending on the view/action; will reduce cluttered and confusion; reduce risk of lag between page load
##### Cons: Will take longer to build out and add functionality. 

##### Initial Thought: take the long road for scalability sake. Don't have to go back and rebuild this thing when/if it gets out of hand


##### Random Thoughts: 
##### For the list of choices - instead of using rows and colums maybe incorporate a list somehow? Need to figure out how to set up columns inside of a list item though
##### list items that are buttons??????????? Will be easy to add an onclick show hide!!!!will also keep the waves effect consistent across the app.
#### Note with the button option I will need to consider adjusting the padding OR finding an alternative to centering the text OR maybe default will work


### TEST 1 - Button inside of list view

![image](https://cloud.githubusercontent.com/assets/18251657/24938892/f2cbe060-1f07-11e7-95df-c0f3bfdabd48.png)

![image](https://cloud.githubusercontent.com/assets/18251657/24938896/f5c1df18-1f07-11e7-993f-6749e0513543.png)
