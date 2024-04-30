# Book's Library - MERN stack app

The current project primarily focuses on showcasing the core functionality of the online library. It includes the following features:

* Adding new books to the library database, including details such as title, author, and publication date.
* Viewing existing books in the library database.
* Editing book details, including title, author, and genre.
* Removing books from the library database.

**Backend CRUD | Backend Router | CORS Policy | MongoDB operations | Frontend CRUD | Frontend Router**



## Tech Stack

**Client:** React + Vite, TailwindCSS

**Server:** Node, Express, MongoDB + mongoose

**Tools:** [Postman](https://www.postman.com/) - for the backend testing


## Deployment

To deploy this project need to follow below steps

 1) Create database instance in [MongoDB](https://www.mongodb.com/lp/cloud/atlas/try4?utm_source=google&utm_campaign=search_gs_pl_evergreen_atlas_general_retarget-brand_gic-null_emea-all_ps-all_desktop_eng_lead&utm_term=using%20mongodb&utm_medium=cpc_paid_search&utm_ad=p&utm_ad_campaign_id=14412646458&adgroup=151115417895&cq_cmp=14412646458&gad_source=1&gclid=CjwKCAjwrcKxBhBMEiwAIVF8rOLGtPvBaCgoueQfTM1OVfVLZvjfu8BBZygiNCYpo2HRW6NxjjgejhoCzTYQAvD_BwE)

 2) A **config.js** file needs to be create in **backend** folder where corresponding local host port and link to database instance needs to be put.

 ```bash
    export const PORT = 5555;
    export const mongoDBURL = 
    //your db url goes her//
 ``` 
 Make sure that collection name is **books-collection** and localhost port **5555**

3) Please run following command in frontend and backend directories to install remaining dependencies:

```bash
npm i
```

4) Run following command into the **backend** and **frontend** directories
   
```bash
npm run dev
```
