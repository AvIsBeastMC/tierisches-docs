# User Registration & Legitimate Animal/Specie Entries
### Wiki Structure
```
wiki
┣ 📂 animal page (🌟 QR Code Page)
	📜 2 Photos (atleast)
	📜 Name
	📜 Basic Description (max 1500 words)
	📜 Type (endangered/vulnerable/critically endangered)
	📜 Is this animal suitable as a pet? (small description)
	📜 Food Type (herbivores/omnivores/carnivores)
	📜 List of species with it's information
	📜 Habitat/Comfortable Climate (forests/winters)
	🔗 Species List
┣ 📂 user page (🌟 QR Code Page)
	📜 name
	📜 email address (used to register)
	📜 profile picture (optional, can be set from dashboard)
	📜 date of birth (dd/mm/yyyy)
	📜 line graph depicting contributions with days (data will be displayed something like this below)
	📜 list of contributions made (in the form of published and under-check edits)
```
<img src="https://i.imgur.com/qCQzk2C.png"  />

### User Authentication
- The user will be required to login/signup through the **authentication flow** of the web application, which shall require a user to fill certain fields of information to prove their identity before any entries that they will be able to do.
- User shall get their own QR code which shall help redirect users go to their profile URL by scanning the User QR which shall show/display contributions done by the user to pages.

### Animal/Species Entry for Registration
- Before entrying, users can also draft their publish like you draft mails that aren't sent due to incomplete work/work to be done in continuation. 
- On entry, an **Publish-Reject Model** has been chosen for the verification and sources for an entry to be published, this shall be applicable to potential contribution/edit that will be done to both General Information of an Animal (page) & addition/changes to Species List of an Animal.
- On acceptance, the edits/additions will be made.
- ⭐ All contributions (being checked and successful edits) will be visible on the page with the name of editor and editor pages will show contributions that are being checked and successful edits, **not declined ones**. 
- On rejection of under-check publish draft, the publish will automatically be saved back to the user's draft vault, reason will also be stated for what was incorrect/inconsistent in the provided information and can be sent for review again.

### QR Generation 
- QR Generation shall only take place for pages and users & once generated, shall remain the same for particular pages.