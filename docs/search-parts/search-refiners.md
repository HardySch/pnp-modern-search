
![Search Refiners](../images/search-refiners-property-pane.png)

#### Refiner Options

Setting | Description
-------|----
Refiners | The search managed properties to use as refiners. Make sure these are refinable. With SharePoint Online, you have to reuse the default ones to do so (RefinableStringXX etc.). The order is the same as they will appear in the refinement panel. You can also provide your own custom labels using the following format RefinableString01:"You custom filter label",RefinableString02:"You custom filter label",... This Web Part supports dynamic translation of taxonomy based refiners with few additional configurations in the connected search results Web Part (see above).
Connect to search results Web Part | The search results Web Part to use on the current page to get filters.

#### Styling Options

Setting | Description
-------|----
Web Part Title | Shows a title for this Web Part. Set blank if you don't want a title.
Show blank if no result | Shows nothing if there is no filter
Filters layout | Choose the template to use to display filters results.

#### Template

##### Persona

The persona template work with technical account name (ex : i:0#.f|membership|pierre.dupond@tenantsharepoint.onmicrosoft.com).

By default, the "Auhtor" managed properties return only real name (ex : Pierre Dupont). 

For the template works with "Author", map crawled properties "ows_q_USER_Author" to a managed properties "RefinableStringXX".

All crawled properties "ows_q_USER_\<name>" and lot of managed properties (People:Manager,People:AccountName ...) return technical account name.