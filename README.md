# TADA
TripAdvisor Data Analysis

About Datathon:-
Datathon is a celebration of data in which teams of undergraduates work around the clock to discover and share insights about large, rich, and complex data sets.

The event is sponsored by the Computer Science Department and the recently launched Data Science Initiative at Brown University. The Data Science Initiative is a cross-departmental program that aims to develop and promote data-driven research and education on campus.

Apart from the competition itself, which is the core of the event, there will be many other supporting activities ranging from educational workshops to opportunities to network with peers and industry representatives.

TripAdvisor Data set:-
You	are	provided	browsing	behavior	of	website	visitors	who	are	shopping	for	a	hotel.	Typically,	a	user	visits	a	travel	website	several	times	for	research	before	they	make	a	final	booking.	It	is	important	to	understand	at	what	stage	of	the	booking	funnel	the	user	is	in	so	that	we	can	personalize	and	optimize	the	website	to	the	user’s	interest.	For	example,	is	the	user	still	in	research	mode	trying	to	choose	the	right	destination	(early	in	booking	funnel)	vs.	the	user	made	decision	on	a	specific	hotel	and	browsing	for	the	best	price	(bottom	of	the	booking	funnel).	The	type	of	information	a	user	is	looking	for	is	completely	different	for	these	two	use	cases	and	it	is	very	impactful	if	we	personalize	the	website	accordingly.		
	
In	the	given	data	set,	we	have	aggregated	the	past	browsing	history	of	the	user	into	several	different	features.	The	objective	of	the	datathon	is	to	predict	the	probability	of	a	hotel	booking	in	their	next	visit	(how	close	the	user	is	to	making	a	final	booking	purchase).	Note	that	for	confidentiality	reasons,	the	column	names	are	masked	or	renamed	without	any	loss	of	interesting	insights	for	data	science.	Also	the	data	is	a	skewed	sample	of	millions	of	users	and	may	not	represent	the	typical	traffic	to	a	travel	website.	Here	are	the	details	of	the	data	set.	All	the	columns	with	the	name	starting	with	‘p_’	are	based	on	the	user	previous	browsing	history.	If	any	of	the	data	is	‘NA’,	assume	the	data	is	not	available	or	unknown.	

BookingPurchase: (User made a purchase) We need to predict this based on the given data	
