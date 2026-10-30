[Home](README.md) | [PC-Revival](PC-Revival.md) | [Team Charter](Team-Charter.md) | [User Stories](User-Stories.md) | [Product Backlog](Product-backlog.md) | [Sprint Backlog](Sprint-backlog.md) | [Agile Logbook](Agile-logbook.md)

4. Product Backlog
4.1 Prioritisation approach

The product backlog is ordered using a practical version of the MoSCoW method:

Must have: Essential to demonstrate the project’s core purpose.
Should have: Important but not required for the first functional version.
Could have: Valuable enhancement once critical functions work.
Won’t have now: Outside the present project scope.

Story points use relative effort. A higher number indicates greater uncertainty, effort or technical complexity. Story points are planning estimates and not hours.

4.2 Prioritised product backlog
ID	Backlog item	Priority	Story points	Main dependency	Completion evidence
|PB01|	Responsive navigation and core page structure	|Must	|3	|None	|Working navigation screenshots|
|PB02|	Service and pricing catalogue|	Must	|3	|PB01|	Services page|
|PB03|	Repair-request form	|Must	|5	|PB01	|Successful form submission
|PB04|	Store repair requests	|Must	|8	|PB03, database configuration|	Database record|
|PB05|  Repair-status tracking	|Must	|8	|PB04	|Status retrieval demonstration|
|PB06|  Refurbished-laptop catalogue	|Must	|5	|PB01, inventory data|	Catalogue screenshot|
|PB07|	Laptop-detail view	|Must	|3	|PB06	|Product-detail screenshot|
|PB08|	Inventory management	|Should	|8	|PB06, authorised access|	Create/update demonstration|
|PB09|	Repair-request administration	|Should	|8|	PB04, authorised access|	Status update evidence|
|PB10|	Quotation request	|Should	|5|	PB02	|Quotation submission|
|PB11|	Contact and enquiry function	|Should	|3	|PB01|	Contact test|
|PB12|	Responsive testing and corrections	|Must	|5	|PB01–PB11|	Desktop/mobile evidence|
|PB13|	Input validation and error handling	|Must	|5|	Relevant forms|	Invalid-input tests|
|PB14|	GitHub Pages deployment	|Must	|3	|Stable build	Published portfolio/project link|
|PB15|	Automated or documented feature testing	|Should|	5|	Implemented stories|	Test results|
|PB16|	Testimonials section	|Could	|3	|Approved testimonial content	|Interface screenshot|
|PB17|	Online payment facility	|Won’t have now|	13|	Payment provider and security design|	Future enhancement|
|PB18|	Automated repair notifications	|Could|	8	|Repair tracking and messaging service	|Future demonstration|
4.3 Product Backlog evidence

Display the following:

Full Trello backlog screenshot.
Close-up screenshot showing priority labels.
Screenshot showing story points.
Screenshot showing acceptance criteria.
Screenshot of backlog items moving from backlog to a sprint.
GitHub evidence of completed backlog items.
Suggested caption

Figure 3: Prioritised PC Revival product backlog. Items are ordered according to customer value, technical dependency and the need to deliver a functional minimum viable product before optional enhancements.

4.4 Product Backlog reflection

The product backlog taught me that not every idea should be developed immediately. PC Revival includes repairs, upgrades, refurbished-laptop sales, tracking, customer communication and possible payment features. Treating all of these as equal priorities would create too much work and increase the risk of leaving essential features incomplete.

I prioritised the functions that demonstrate the core value of the system: displaying services, accepting repair requests, showing refurbished laptops, storing information and producing a usable responsive interface. Functions such as testimonials, automatic notifications and online payments are useful, but they should not prevent the core system from being completed.

I also learned that dependencies affect priority. A repair-status page has limited value until requests can first be submitted and stored. Similarly, inventory management depends on a defined inventory structure. In future, I would review the backlog after every sprint and separate priority from effort more carefully. A high-effort story may still be essential, while a low-effort story may offer little immediate value.
