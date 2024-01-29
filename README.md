# Climbers-Club

Visit the website [here](https://climbers-club-se9p.vercel.app
)

Climbers-Club is a website created to provide guidance and inspiration for climbers, particularly those interested in rock climbing outdoors. This project was developed for educational purposes only.


## Business Goals

1. Advise users on climbing and updates within the climbing world.
2. Inspire users to get the most out of climbing and maybe go on bigger climbing trips.
3. In the future i'd like to interrgrate a E-Commerce store and sell items to users from the website
4. Build a database of users for future communication.

## User Goals

1. Easily find useful information and tips for climbing.
2. Access a helpful guide on climbing training and goal setting.
3. Link to to other trusted pages for more information.
4. Sign up for the newsletter to receive direct content.

## UX Strategy

- Target Users: Aged 16-65+, past/future climbers, and those interested in climbing.
- User Expectations: Clear, concise, and easy-to-find information with beautiful, inspiring visuals.

## Scope

To achieve the desired user and business goals, the website includes features such as:
- Responsive header and menu bar.
- Detailed guide to training and linking to further videos to gain more knowledge.
- Community sign up form.
- Newsletter sign-up form.

## Structure

1. **Home/Introduction & Newsletter Signup:**
   - A welcoming introduction image to the website and the sections below provide direction for the user.

   - Users can sign up for Climbers-Club's newsletter for future updates and content.
![!\\[Newsletter home image screenshot\\](image.png)\](<docs/newsletter and home screen.png>)](docs/newsletter-and-home-screen.png)

2. **Summit Spectrum:**
   - Section filled with valuable tips for climbing and also background stories and news within the climbing world.
![!\[summit spectrum screenshot of weekly challenges and goals\](image.png)](docs/summit-spec-goals.png)
3. **Community Hub:**
    - Users can sign up to be part of the community. (int eh future this would send them a link to log into a fully developed members area)
  ![ !\[Community Hub form screenshot\](image.png)](docs/communityhub-form.png)



## Surface & Technologies Used

### Surface

- Fonts: 'Lato', 'Oswald'
- Fully responsive design for optimal viewing on various devices.

### Technologies Used

- HTML, CSS, JavaScript (for responsive features).
- Google Fonts for 'Lato' and 'Oswald'.
- Font Awesome for social media icons.
- Various tools for development, validation, and testing i.e.: Vercel (for deployment)

# Features

## Climbers Club | Home Page:

### HTML Structure:
- Standard HTML5 structure.
- Utilizes Bootstrap 4 for styling.

### Navigation Bar:
- Responsive navigation bar with Bootstrap's navbar class.
- Links for "Home," "Summit Spectrum," and "Community Hub."

### Modal:
- A modal encouraging users to sign up for the newsletter.
- Includes a form with an email input and "Sign Up" button.

### Hero Image:
- Hero section with a call-to-action button for newsletter sign-up.

### Story Sections:
- Multiple story sections with images.
- Each section includes a title, image with hover effects, and a brief description.
- External link for "Gear Reviews and Recommendations."

### Footer:
- Educational disclaimer.
- Social media links using Font Awesome icons.
- Website directory links for navigation.

### JavaScript Libraries:
- Bootstrap JS and Popper.js for responsiveness.
- Font Awesome for social media icons.

## Climbers Club | Summit Spectrum:

### HTML Structure:
- Standard HTML5 structure.
- Utilizes Bootstrap 4 for styling.

### Navigation Bar:
- Responsive navigation bar with Bootstrap's navbar class.
- Links for "Home," "Summit Spectrum" (active), and "Community Hub."

### Hero Section:
- Hero section for a visually appealing introduction.

### Content Sections:
- Multiple sections with titles and paragraphs related to climbing topics.
- Embedded YouTube videos for additional media content.

### Footer:
- Educational disclaimer.
- Social media links using Font Awesome icons.
- Website directory links.

### JavaScript Libraries:
- Bootstrap JS, Popper.js, and Font Awesome for responsiveness.

## Climbers Club | Community Hub:

### HTML Structure:
- Standard HTML5 structure.
- Utilizes Bootstrap 4 for styling.

### Navigation Bar:
- Responsive navigation bar with Bootstrap's navbar class.
- Links for "Home," "Summit Spectrum," and "Community Hub" (active).

### Hero Section with Form:
- Hero section for encouraging users to sign up.
- Form with fields for first name, last name, email, and climbing preferences.
- Form submission to "https://formdump.codeinstitute.net/" in a new tab.

### Footer:
- Educational disclaimer.
- Social media links using Font Awesome icons.
- Website directory links.

### JavaScript Libraries:
- Bootstrap JS, Popper.js, and Font Awesome for responsiveness.


## Testing

### Devices Tested:

- MacBook 13-inch
- iPhone 10
- iPhone 12
- iPhone 13
- Huawei Laptop 15-inch
- 24-inch HP Monitor

### Browsers Tested:

- Chrome
- Microsoft Edge
- Safari (on iPhone)

### CSS Validation:

- Tested CSS with [W3C Jigsaw Validator](https://jigsaw.w3.org/css-validator/).
- All CSS passed validation.

### Call to Action Button:

- Tested the call-to-action button on the home page (Gero) by clicking.

### Sign Up Form:

- Tested each box on the sign-up form on the community page by clicking.

### Image Overlays:

- Ensured image overlays correctly navigate to the intended destination by clicking.

### Navbar Testing:

- Verified that the navbar displays the correct page by checking the URL.

### Social Links:

- Tested each social link by clicking to confirm they open corresponding news pages in a new tab.

### Form Submission:

- Confirmed that completing forms opens a new tab to enhance user experience, avoiding the need for the back button.

### Responsive Design:

- Checked the website's responsiveness on various devices to ensure a consistent user experience.

### YouTube Videos:

- Ensured embedded YouTube videos do not autoplay on page loading.
- Verified that users have control over playing and toggling the volume of the embedded videos.

These comprehensive tests cover various aspects of functionality and user experience, including the proper behavior of embedded YouTube videos.


## Deployment

The Climbers Club website is deployed using [Vercel](https://vercel.com/) with seamless integration with the GitHub repository. Follow the steps below to deploy the website:

### Vercel Deployment Steps:

1. **Login to Vercel:**
   - Log in to your Vercel account or sign up if you don't have an account.

2. **Create a New Project:**
   - Click on the "Create" button to start a new project.

3. **Connect GitHub Repository:**
   - Choose the "Import Git Repository" option.
   - Select your Climbers Club GitHub repository.

4. **Configure Project Settings:**
   - Configure your project settings, including the branch you want to deploy (usually the main/master branch).

5. **Build Settings:**
   - Vercel will automatically detect the type of project (Next.js, React, etc.).
   - Ensure the build settings are appropriate for your project.

6. **Environment Variables:**
   - If your project requires environment variables, add them in the Vercel dashboard.

7. **Deploy:**
   - Click on the "Deploy" button to start the deployment process.

8. **View Deployment:**
   - Once the deployment is successful, Vercel will provide you with a unique URL for your deployed Climbers Club website.

### Automatic Deployment:

With Vercel's GitHub integration, every push to the configured branch on GitHub triggers an automatic deployment. This ensures that your deployed website stays up-to-date with the latest changes in the GitHub repository.

### Manual Redeployment:

If needed, you can manually trigger a redeployment on Vercel:
   - In the Vercel dashboard, go to your project.
   - Click on the "Deployments" tab.
   - Click on the "Redeploy" button for the specific deployment you want to update.

Now, your Climbers Club website is live and can be accessed through the provided Vercel URL.

Feel free to check the [Vercel Documentation](https://vercel.com/docs) for more detailed information on deploying and managing projects.

## Acknowledgements

- **Commit Messages:**
  - Acknowledge that the commit messages started off poorly but improved over time. By the end of the project, the goal was to provide clearer and more descriptive commit messages.

- **Code Resources:**
  - **Stack Overflow:**
    - A valuable resource for troubleshooting and finding solutions to coding challenges. [Stack Overflow](https://stackoverflow.com/)

  - **W3C:**
    - The World Wide Web Consortium's resources were crucial for validating and ensuring standards compliance. [W3C](https://www.w3.org/)

  - **ChatGPT:**
    - Leveraged ChatGPT for assistance and guidance during the development process.

  - **Personal Notes from Code Institute Course:**
    - The Code Institute course materials provided essential knowledge and guidance. [Code Institute](https://codeinstitute.net/)

- **Images:**
  - All images used in the Climbers Club website are original and owned by [Your Name].

## Resources

The following resources were instrumental in the development of the Climbers Club website:

- **Stack Overflow:**
  - [Stack Overflow](https://stackoverflow.com/) - A vibrant community of developers offering solutions to coding queries.

- **W3C:**
  - [W3C](https://www.w3.org/) - The World Wide Web Consortium's official website for web standards.

- **ChatGPT:**
  - OpenAI's ChatGPT was utilized for obtaining guidance and solutions during the development process.

- **Code Institute:**
  - [Code Institute](https://codeinstitute.net/) - The official website for Code Institute, providing comprehensive courses in web development.

These resources played a crucial role in overcoming challenges, improving code quality, and enhancing the overall development experience.
