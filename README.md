# ChadaInventory

The Chada Inventory program is the 3rd project from my Programming Languages course. 

Summarize the project and what problem it was solving.
In this program we needed to filter through a file with items sold. 
The problems that this problem solves are
Categorically recording by type items sold, and saving the quantities.
Saving that information to an external .dat file
And finally presenting that informaiton in a user friendly way to the user of the program. 

What did you do particularly well?
In this program I think I did particularly well in separating out classes. In this program I created an item class and an inventory class. The inventory class contains a vector of the item class, while the item class has exposed features to make it easier to keep track of quantities. I also chose to do it this way because it would be easier to convert it to the MVVM design pattern in the future. 

Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
Where I could enhance my code would be the inclusion of a service class to handle the IO in the program. So create another class, i.e. FileHandler, that would handle the creation of the backup file as well as the reading of the input file. This would have cleaned up the functionality of the code a little more. 

Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?
I didn't particularly find anything particularly complicated within this code. It was pretty straight forward and leans on previous experience I have. One thing that I am adding to my theoretical toolbelt is the use of pointers. While a complicated concept at first, these do have handy uses within C++

What skills from this project will be particularly transferable to other projects or course work?
Following an OOP structure will transfer well to other projects. Being able to isolate out functions and data structures into their own classes will not only work well in other projects but also increase expandability as well as readability. 

How did you make this program maintainable, readable, and adaptable?
I made this program maintanable by following OOP standards and separating functions and data structures. I made it readable by commenting the code (albeit most of the comments aren't really necessary), and adoptable by again separating out the data structure.
