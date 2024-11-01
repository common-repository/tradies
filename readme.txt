 === TRADIES ===
Contributors: tradies
Donate link: https://tradiescrm.com/
Tags: To do, CRM, customer relationship manager, kanban, Kanban to do, Trello, GTD, asana, to dos, business system, systemise business
Requires at least: 4.0
Tested up to: 5.2.2
Requires PHP: 7
Stable tag: 2.2.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
  
== Description ==

Tradies is a simple job quoting and invoicing plugin along with a simple To do's system to manage projects on the dashboard. Forms filled on website frontend by site visitors can prefill a quote in the backend for you as a draft ready to be sent out once job is priced up
Tradies was made for the construction industry that helps tradies, builders, contractors or any small business wanting run their business within wordpress. 
 
== Quoting == 

Easily create quotes, manually through the admin or using a form on your website (you or potential clients can use this form to create quotes), edit, add images, html or whatever you like. When ready, download as pdf or print or send to client, where the potential client can view the quote online and hit accept button if they approve or send a message back to you why they disapprove. Once the quote is approved you could have it automatically convert to an invoice. Further, you can track if the quotes been read. A truly professional system, which will help you convert more leads.

== Invoicing == 

Easily add items to your invoice from a preconfigured selection of products and services you offer.  Once you are happy,  download as pdf or print or send your invoice directly by email which will present the invoice to your client online. Again, you can track if the invoice has been read. Once the client receives the invoice they are able to pay through paypal via a link online or whatever method they would like to pay with.

== To do's ==

Business can feel overwhelming, but it doesn’t have to. The To do section based on GTD lets you keep track of everything in one place, so you can get it all done and enjoy more peace of mind along the way. To do items can be displayed on your dashboard while you work throughout the day and moved around when priorities change or new tems added, just as you do in Trello and deleted as they are compeleted. Tags are used to group To Do items, so that you can see a group of To dos together and improve clarity. 
 
== Features == 

- Drag/drop To do section based on the Getting Things Done®  by David Allen's GTD® Methodology. 
- proposals/Quotes
- invoicing/Paypal Payments
- To do has 'types', so a to do can be customised to read 'buy', or 'research' or 'build', for example when shopping for material at the hardware for your current project you can select the buy type and see other projects which may need material to be purchased as well, so your not wasting time going back and forth to the hardware.
- The dashboard lists the selected to do items, in rows which can be moved around just like the Trello - kanban type system
- To dos also have Tags which allow you to group certain to do's together. For example you could create a tag called 'staff ' and that way when your having meetings with your staff you can only list to do's in that group 
- drag and drop, positioning to dos to the level of priority while within the table view
- auto proposal creating from forms filled in and sent from front end of website.
- To do's on dashboard like trello and asana
- job sheet button on quote and invoices creates job sheet ready for printing
- plus much more being currently developed

== Installation ==
 
 
1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go through the settings and fill out as much as you can, and start creating to do's, quotes and invoices

 
 == Screenshots ==
 
1. To do items are automatically place on the dashboard. Move items around. Left column items usually needs to be done soon. Right columns not so important.
2. Create invoices easily while on the road on your mobile.  
3. To do in list view on the mobile.
4. Easily create quotes manually or auto created when website form is filled on your website.
5. When visitors on your website want a quote, they could fill out a form which wll auto generate a quote in the back end for you to work on with prefilled fields.
6. The CRM is made in way to that you should us the GTD - Getting Things Done® by  David Allen's to help run your business smoothly while you grow without being overwhelmed by projects.
 
== Overview ==
 
1. Help Bulders, trades people organise their day
2. To do system based on Getting Things Done®  by David Allen's GTD® Methodology
3. To do's auto created on Trello like dashboard
4. Quick, easy proposal creation, with accept now button when sent to client
5. invoicing system
 
 
 
== Frequently Asked Questions ==
 
= I Need help =
 
Please get support from us via the wordpress forums 

= Can i capture form details into the CRM =
 
yes, install the 'contact 7' plugin and use the following code to create a form and use the short code created by Contact 7 on any page you like to automaitcally create the form.

<style>
.col-container {
  display: table;
  width: 100%;
}
.col {
  display: table-cell;
  padding: 16px;
}
</style>
 
<div class="col-container">

  <div class="col" >

<label>Your Name
    [text* tradies_client_name] </label>

<label> Phone
    [text your-phone] </label>
Address<br />
    [text tradies_client_address]
  </div>
  <div class="col" >

<label> Company Name 
[text company-name] </label>

<label> Your Email 
    [email tradies_client_email] </label>
    
  </div>
</div>
<div class="col-container">
  <div class="col" >

<p>Overview of work required<br />
    [text tradies_title] </p>

<p>Description of work required.. Budget, timeframe <br />
    [textarea tradies_description 20x4] </p>

<p>Extra info such as size, links etc
    [text tradies_client_extra] </p>
</div>
</div>
 

[submit "Send"]
 
 
 
 
 -------------------------------
 
 

 Under the mail tab, in the messages section paste the following so that you recieve the above details when filled out.
 
 From: [tradies_client_name] <[tradies_client_email]>
Subject: [tradies_title]

Message Body:
Phone: [your-phone]
Address: [tradies_client_address]
Company name: [company-name]
Description: [tradies_description]

[tradies_client_extra]

------------------------------- 
 
 
 


= My invoices/quotes dont show  =

1. make sure you enterd all the details in settings section
2. try a different browser, if this solves the issue, you need to clear your cache and/or cookies.
3. If your using Elementor de-activate it and re-activate it
4. If your using Elementor, and you have setup single-page theme under the theme builder in the templates menu for Elementor Pro
this casues a conflict since the invoices use the single page to display invoices/quotes.
to over come this you need to delete this entry and create a custom single-page template within your theme 

= Industries that can use this CRM =

Electricians
Plumbers
Handyman
Builders
Painters
House Cleaners
Air Conditioning
Arborists
Architects
Balustrade fabricators
Bathroom Renovators
Blind Suppliers
Bricklayers
Building Designers
Building Inspections
Cabinet Makers
Carpenters
Cleaners
Concreting
Curtain/blind isntallers 
Demolition firms
Door makers/installers
Drafting providers
Excavationers
Mechanics/Garages
Gardeners
Gas Fitters
Fencing/Gates
Glaziers
Gutter Cleaning
Security Companies
Home Theatre installers
Hot Water Systems installers
Insulation installers
Interior Designers
Kitchen maker
Landscapers
Electrician/Lighting
Pest Control
Plastering company
Pool Fencing
Pressure Cleaner
Rain Water Tanks
Removalists
Renderer/Rendering
Retaining Walls
Roofing / Roof Repairs
Rubbish Removal
Security Screen Doors
Shopfitters
Shower Screens
Solar Power
Tilers / paving firms
Timber Flooring
Tree Fellers
Wardrobes maker
Waterproofing
Window Cleaners
Window Repair
Window Tinting
Tradies can be used by anyone really, such as web designers, accountants, manufacturers etc. 


== Changelog ==

= 2.2.6 05/10/2019 =
* fix: bug fixes

= 2.2.5 21/9/2019 =
* Improve: Added functionality to convert invoices/quotes to pdf
* Improve: Added functionality to convert invoices/quotes to print
* fix: bug fixes


= 2.2.3 10/9/2019 =
* fix: bug fixes
* Improve: Chenged To do section

= 2.2.2 19/8/2019 =
* fix: minor bugs

= 2.2.1 19/8/2019 =
* fix: minor bugs
* Improve: added setting to enable quicklinks, admin wide

= 2.2.0 18/8/2019 =
* fix: notice errors on jobsheet
* Improved: added line items to jobsheet
* Fix: fixed issue with emails not arriving
* Improved: ajax search icon added beside to do, invoice buttons

= 2.1.9 16/8/2019 =
* fix: invoice and jobsheet bug 

= 2.1.8 14/8/2019 =
* missing: directory includes/tradies-admin-search/

= 2.1.7 14/8/2019 =
* Added: shortcut buttons in header 
* Added: Ajax live search 
* Added: prevent subscriber accessing plugin sections

= 2.1.6 10/8/2019 =
* fix: phone number bug 

= 2.1.5 9/8/2019 =
* fix: minor bugs 
* added details to overcome Elementor conflicts
* added users button to CRM menu
* sanitised/secured certain areas

= 2.1.4 8/8/2019 =
* fix: bugs causing looping logouts
* Improved: added jobsheets printout facility
* Improved: Added phone number to client
 
= 2.1.3 6/8/2019 =
* fix: bugs
* Improved: moved create terms/taxonomy to plugin activate function
* fix: to do post limit increase fom default 5 to 150 to display correctly on dashboard
 
= 2.1.2 2/8/2019 =
* removed: simple custom post order test files

= 2.1.0 – 1/8/2019
* added: drag and drop functionality on to dos table
* added: proposal and invoicing system 
 
  
== Plugin design/programming by ==
- [Hype Studio](https://hypestudio.com.au)

