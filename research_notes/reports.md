# Reports

> System Excel, Word, and other Reports. What Types of them should we introduce in our system? And what tools best suited to do them using Python/Django?


from the client view:
To make summery or a report we have to simply use html taples and make some modifications in the Django files and link both

my intuition about the form of report is:
| Item	| price/item	| quantity	|total price	|

We have to make sure that the user logged in by importing and using "LoginRequiredMixin" and add it in the class' arguments or use "LoginRequired" and wrap the wanted class with "@Login_Required"

views.py
	the class for making the report -inheret from imported "View" class- will use the data from other classes like "add_to_chart" to get the required information.
	define a get() method to view the html file which is get(self, *args, **kwargs): return render(self.request,'file.html')
	in this class we also get the ordered things, and pass it to the html file

urls.py
	create path(class.as_view)

templates directory
	the html file containing the taple

models.py
	"Order_Item" class contain the quantity of the item and the item type from which we get "Item_Detail"
	def a method getting total price/item using mathematical operations usin the information provided(about the item, quantity, offers)
	def another method getting the total price of all items and link it to the last row in html file

file.html
	iterate through the items in the columns of the taple and update the values
	

for more info about reports "https://www.youtube.com/watch?v=dv9vKusSrDI&t=43s"

==========================================================================================
