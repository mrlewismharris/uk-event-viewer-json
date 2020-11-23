- [ ] convert json data to js classes objects so they can be sorted properly
  - [x] create object class
  - [x] loop json data into individual objects/class instances
  - [x] add function to "print" event object into the table
  - [x] add method for default sorting
  - [x] add class collections? (not available this isn't java dumbass just use object arrays)
  - [x] add javascript onclicks to table headers (switch done - sorts aren't working)
  - [ ] add sorting onclick of table headers
- [ ] Add "Show past events" button (show/hide events with date older than current date)
- [ ] simple search function
- [ ] give past events a different colour background
- [ ] add advanced search function
  - [ ] checkbox search for regions
  - [ ] website link (containing certain keywords)
  - [ ] search by region map (clickable svg)
  - [ ] city search
- [ ] Add AJAX
  - [x] Loop loads json data
  - [x] Counter to show when page was last refreshed
  - [ ] Counter to show when data was last available
  - [x] Loop replaces table data


# Ideas:
 - Add a "password" field on the google form so just anyone can't add data without the password. The way this would work is by collecting a plaintext password from the field and adding it as another column in the Google sheet, then in another sheet in the same document will analyse the sheet of ALL the entries submitted, and only display the one's with a matching password. Very primitive and plaintext - but kinda fun. Then the user can switch between a list of "view all entries" and "view verified entries only". I can also manutally add the correct password to entries I've verified on the google sheet. Aaah I just realised a problem: If the whole document is being shared then users can just view the plaintext password! Kappa wtf. Maybe have a "master page" with all entries, another page with all entries but passwords stripped, and another page with verified entries and passwords stripped... I'm not sure if I can disable so the document's data can only have 1 sheet viewed? I'll have to see in google sheets... tbc
