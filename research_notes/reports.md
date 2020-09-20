# Reports

> System Excel, Word, and other Reports. What Types of them should we introduce in our system? And what tools best suited to do them using Python/Django?


Super User
	# users (shop admins-accountantas) ==> detailed if needed
	change in users (in||out)
	Bugs Reported
======================================================
Government Supervisor
	Total income over time
======================================================
Shop Admins
	#users(Roles) ==> detailed if needed
	users change (in||out)
	Marketplace/Delevery history
	-------------------------------------
	most saled product
	least saled product
	most penefit product
	-------------------------------------
	product expiration date/sold items
======================================================
Accountant
	# products ==> #items in each product
	# sold products over time
	--Marketing funnel-- when marketing is applied(reach>lead generation>conversion>purchase)
	--Sales funnel-- (interested'visit'>lead'contact info'>qualified leads'add to cart'>Conversion'booking&purchase')
	--Finantial matrex-- (Gross profit>Operating income>net income, Gross margin etc.)


=========================================================================================================================


To make the report we will devide it in 3 stages

1)getting data from database using python pandas lberary (multiindexing or pivot taples)
2)passing this data to Django template to make html file (...)
3)converting this file to pdf if needed using pdfkit in python
	

