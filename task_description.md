## Task Description: 
Our company focuses on quality services with honest user reviews. Currently, we are looking for a front-end web developer to build a full-stack website using `React`, `firebase`, `react router`, `node`, `express`, `mongodb` etc. 

Make sure your website design is unique. Visit ThemeForest, Dribble, google, etc., to get some ideas.

Try to explore component libraries other than DaisyUI. Remember, a unique project will add more value to your portfolio.

However, your website **cannot** be related to your **previous assignments** or any **practice project** shown in the course modules or our **conceptual sessions.** If any similarities are found, you will get **zero(0)** as a penalty.

## Service review website

**Examples:** Online delivery service review, Online trainer review, travel/tourist service, Lawyer, Photographer (wedding photographer, sports photographer, journalism photographer, wild photographer, etc.), Immigration & VISA Consultant, Tax Lawyer, Accountant Service, Doctor/Dentist (single doctor. not a hospital or a diagnostic center), Journalist, YouTuber, Cloud kitchen, etc. If you have another idea for an individual service provider, please let us know before proceeding. (Please note that your website can not be related to a marketplace freelancer working on fiver, Upwork, etc. It can not be a portfolio website)

### Main Requirements

1. The homepage will have a Navbar, a slider/banner/ a meaningful section. Under the navbar, display a list of services. There will be at least 6 services in the database, but here, you will `limit` the number to only 3 i.e. on the home page, you will show maximum of 3 services (this should be done in the backend). Also,  add a meaningful footer.
2. There will be a " **see all**" button/icon under the 3 services. When clicking the button/icon, take the user to the _/services_ route and show all the services on that page.
3. Add two extra sections on the home page. Make sure it is unique and relevant to your website.
4. The services of the home page and the services of the services page will have the name of the service, image, rating(optional), price, a short description(maximum 100 characters), and a view details button with each service card.
5. When clicking on the image of the service, the picture will be viewed on full screen. Explore the package [react-photo-view](https://react-photo-view.vercel.app/en-US) for that.
6. On clicking the view details button, the user will be taken to the service details page: _/services/:id_ route
7. The service details route will have two sections.

	7.1. **Service section:-** show all the details of that Service with full description.
	
	7.2. **Review section:-** there will be a review section where a user can see others' reviews of that service. A review should contain a text, name, and image of the reviewer, rating(optional). The user can also **add his/her own review** for that service. But he needs to log in first. If the user is not logged in(use conditional rendering), show a text like: Please login to add a review. After clicking the login button/link, take him to the login page. Otherwise, show a form with a text area and a button to add his review(rating is optional). Please store the user info (email, etc.) and service info (service id, etc.) with each review to display the reviews correctly with the relevant service.

8. Implement email/password-based authentication and at least one social login(google, Facebook, GitHub, etc.) authentication. Please skip the email verification part here, because it will create some inconvenience for the examiner. It is important for the examiner to be able to check your authentication without any hassle. If you want, you can add email verification after getting the assignment result.
9. Once a user is logged in, he/she will see more options like My reviews, Add service, and the logout button in the navbar.
10. The "My reviews" page will be a private route and show only the reviews that the current user added either in a table or in cards with relevant information like - service name, review etc. There will be two buttons/icons - edit review(details in the bonus part) and **delete review** with each review. On clicking the delete button/icon, you have to delete the review, and it won't show up on that service page anymore. When the delete is successful, a toast/modal with a message will pop up to inform the user. If the user doesn't add any review, the page will show 'No reviews were added' at the middle of the page
11. On the "Add service" page(also a private route), you can **add a service** and that service will be shown on the home page. When the service is added successfully, a toast/modal with a message will pop up to inform the user.
12. No Fake data (data must be hosted on the database). The database could be MongoDB or any other NoSQL database.
13. Add one more public route: Blogs. You will have to answer the following questions on the Blog page

	- Difference between SQL and NoSQL
	- What is JWT, and how does it work?
	- What is the difference between javascript and NodeJS?
	- How does NodeJS handle multiple requests at the same time?

### Bonus Requirements

1. Your Readme file for the client-side repo should have details about your project's features and functionalities in bullet points(at least five bullet points) and your live link. Adding a meaningful readme file for the server-side repo is optional.
2. At least 15 meaningful GitHub commits for the client-side and 8 meaningful commits for the server-side repository.
3. Your code should be clean and organized. Comments should be added where necessary

1. The **title of the page** will change with the page you visit. It should not be the same for every route
2. Add a meaningful favicon
3. Add a **spinner** on the services page, and the login and register page. If data is loading, a spinner will be displayed.
4. use the **Environment** Environment variable on both the client (firebase config) and server-side (mongodb credentials, Access token secret). Use .gitignore file on the server side.
5. Implement the basic version of the **JWT**  **token** for email/password-based authentication. Upon login, you will create a jwt token and store it on the client side, and for the "My reviews" page, you will send the token and verify the user. Implementing 401 and 403 is optional. 
6. In the "My reviews" page, clicking the **edit review** button/icon shows that review in a modal/in a new route and lets the user update it.
7.  **Simple challenge** In the service details page, **sort the reviews in a descending order** by inserting time(you have to keep the inserting time when you add a review, you can do it with the Date object, or you can explore MongoDB documentation). You will have to implement this code on the server side.

### Optional
1. Use pagination on the services page.
3. Show the rating with star icons in a user review
4. 2. Try to use a better-looking confirmation dialogue other than the browser's default confirm.
3. On the `add a service` page, try to implement direct image upload from your computer. This image can be hosted on a third party image hosting like imgbb or directly to mongodb
4. Add some animation while applicable.
5. Please Use icons whenever applicable and use fonts (google fonts)
6. Make the footer a little more realistic with the copyright symbol and year.
7. Optimize your images
8. Add something extra of your own. This will help you in the future.

### Additional information:
1. You can use vanilla CSS, any CSS library, framework, or component library you want.
4. If possible, try another component library other than daisyUI
5. If needed, you can mix a CSS framework with a component library
6. You may use `react hook form`, basic html form or any library for authentication
7. Store JWT token in http only cookie (alternatively, feel free to store it in the Local storage for this assignment)
9. Try to host your site on Firebase (Netlify host will need extra configuration)
10. Try to host the server on Vercel

### What to submit 
1. Your client-side code GitHub repository
2. Your server-side code GitHub repository
3. Your live website link


Have FUN! Have Patience. 
