<h1>TaskPro - FullStack App</h1>

<h2>Project Links</h2>
<ul>
  <li>
    <a href="https://taskpro-beryl.vercel.app">Live App</a>
  </li>
  <li>
    <a href="https://www.figma.com/design/fJF13s2UlxPIwTMcPVrSiz/TaskPro">Figma Design</a>
  </li>
  <li>
    <a href="https://taskpro-server-delta.vercel.app/api-docs/">API Documentation</a>
  </li>
</ul>

<h2>Description</h2>
<p>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>TaskPro</b> is an intuitive Kanban board application designed to help users organize and manage their projects and tasks efficiently. Inspired by tools like Trello or Jira, TaskPro offers a seamless experience for tracking progress and staying productive, ensuring that deadlines are never missed.
</p>

<h2>Features</h2>
<ul>
  <li><b>User Authentication</b>: securely create an account and log in, or use Google authentication for quick access to your personal workspace.</li>
  <li><b>Password Recovery</b>: easily reset the account password by entering your email and receiving a reset link directly to your inbox.</li>
  <li><b>Customer Support</b>: get in touch with our support team by filling out a form with your comment and sending it directly for prompt assistance.</li>
  <li><b>Edit Profile</b>: customize your profile by updating your name, email, and optionally adding a profile picture.</li>
  <li><b>Select Theme</b>: choose from three available themes: light, dark, or violet, to personalize your application's appearance.</li>
  <li><b>Project Management</b>: create, update, and delete boards, which will be organized in a list for easy selection.</li>
  <li><b>Column Management</b>: configure each board by creating, updating, and deleting columns for optimal structure and making it easier to organize tasks into different categories.</li>
  <li><b>Card Management</b>: create, update, and delete cards within columns to represent tasks that include essential information such as name, description, priority, and deadline.</li>
  <li><b>Filtering</b>: select the priority level to display only those cards that match the chosen priority, making it easier to focus on the desired tasks.</li>
</ul>

<h2>Frontend</h2>
<ul>
  <li><b>Technologies</b>: React, TypeScript, Redux, Styled-components</li>
  <li><b>Project Setup</b>:
    <ul>
      <li><b>Vite Template</b>: For a swift and efficient build process.</li>
      <li><b>Deploy</b>: Vercel.</li>
      <li><b>Type Safety</b>: Ensured by TypeScript configuration for strict type-checking and an enhanced development experience.</li>
      <li><b>Linting</b>: Enforcing ESLint configuration for a clean and robust codebase.</li>
    </ul>
  </li>
  <li><b>Code Organization:</b>: 
    <ul>
      <li><b>Module Type</b>: ECMAScript Modules (ESM).</li>
      <li><b>Components Type</b>: Reusable functional components.</li> 
      <li><b>Custom Hooks:</b>: Developed to encapsulate and reuse logic across different components, enhancing code maintainability and consistency.</li> 
      <li><b>Utils:</b>: Helpers functions implemented to perform common tasks, improving code readability and avoiding duplication .</li> 
    </ul>
  </li> 
  <li><b>State Management</b>:
    <ul>
      <li><b>Redux</b>: Used for centralized state management in the application.</li>
      <li><b>Redux Toolkit</b>: Integrated to simplify Redux configuration, by utilizing slices to modularize state logic, creating actions and reducers more efficiently, and streamlining the setup process for improved code readability and maintenance.</li>
      <li><b>Redux Persist</b>: Implemented to persist the application state across sessions, ensuring data consistency and improving the user experience by retaining state even after page reloads.</li>
    </ul>
  </li>
  <li><b>API Client</b>: 
    <ul>
      <li>Created a custom <b>"Axios"</b> instance to encapsulate the configuration and logic, ensuring consistency and reusability across the application.</li>
      <li>Configured to handle HTTP requests to the server, with a base URL and credentials included.</li>
      <li>Implemented <b>response interceptors</b> to manage authentication errors, initiating a forced logout for user reauthentication when a <b>401 Unauthorized</b> response occurs.</li>
    </ul>
  </li>
 
  <li><b>Styling</b>: 
    <ul>
      <li><b>Styled-components</b>: Used for writing isolated styles for each component, ensuring clean and maintainable code, including automatic prefixing for cross-browser compatibility, theming management, dynamic styling through props, and nested syntax.</li>
      <li><b>Cross-Browser Compatibility</b>: Ensured through the use of <i>"modern-normalize"</i> and custom reset properties, providing consistent rendering across different browsers.</li>    
      <li><b>Responsive Design</b>:
        <ul>
          <li>Applied through a <b>mobile-first approach</b>, ensuring the application is optimized for mobile devices first.</li>
          <li>Using media queries and flexible layouts to adapt the design effectively to various devices and screen dimensions.</li>
          <li>Using <i>"react-responsive"</i> library, which conditionally renders components based on the size of the viewport.</li>
          <li>Utilized responsive images and backgrounds, with dimensions and versions tailored to ensure optimal visual experience across different screen sizes and pixel densities - <b>Retina display support</b>.</li>
        </ul>
      </li>
      <li><b>Sprite Technique</b>: Consolidated all vector icons into a single sprite file, enhancing performance by reducing server requests and improving page load times, while making icon access and management easier.</li>      
      <li><b>Themes</b>: The application supports three distinct themes: dark, light, and violet, allowing users to choose their preferred visual appearance.</li>
      <li><b>Transitions</b>: Implemented to provide smooth effects during user interactions and particularly when changing themes, maintaining consistency across various elements.</li>
      <li><b>Animations</b>: Incorporated custom animations and animations from the <i>"animate.css"</i> library to enrich the visual appeal and create an engaging user experience.</li>
    </ul>
  </li>
  <li><b>User Experience (UX)</b>: 
    <ul>
      <li><b>Navigation</b>: Designed to be intuitive, guiding users and clearly indicating their current location within the application.</li>
      <li><b>Loading Screen</b>: Used for the login and logout processes, providing visual feedback and improving the user's interaction with the application.</li>
      <li><b>Loading Spinner</b>: Displayed at key moments in the application, notably when awaiting server responses, providing users with real-time feedback.</li>
      <li><b>Modal Closure Options</b>: When a modal is open, it can be closed in multiple ways: by clicking the <b>"X"</b> button, by pressing the <b>"Esc"</b> key, by performing a mouse down action outside the modal, or automatically upon submitting the form within the modal and receiving a positive response from the server.</li>
      <li><b>Form Feedback</b>:
        <ul>
          <li><b>Placeholders</b>: Implemented to indicate the necessary data for each field, guiding users in completing the forms correctly.</li>
          <li><b>Error Indicators</b>: Added visual effects, such as red borders and error messages, to alert users when a field is required or contains invalid data.</li>
          <li><b>Submit Button</b>: Becomes disabled if any errors are detected, preventing the submission of incorrect data to the server.</li>
          <li><b>Password Visibility Toggle</b>: Included a show icon for password fields, allowing users to toggle the visibility of their password, enhancing usability.</li>
        </ul>
      </li>
      <li><b>Notifications</b>: Utilized <i>"react-toastify"</i> library to display different types of notifications, including success, error, and warning messages, particularly when a response is received from a server request, providing immediate feedback to users.</li>
      <li><b>Forced Logout</b>: Implemented a mechanism that, upon receiving a 401 response from the server (indicating the user is not authorized), forces a logout, requiring the user to reauthenticate.</li>
      <li><b>Drag & Drop</b>: This feature allows users to easily move and organize cards within the application, enhancing usability and interaction efficiency.</li>
      <li><b>Ellipsis Tooltip</b>: Using the <i>"tippy.js"</i> library to handle visually long elements by truncating them and displaying an ellipsis, which reveals the full text when users hover over it, enhancing readability.</li>
    </ul>
  </li>
</ul>

<h2>Backend</h2>
<ul>
  <li><b>Technologies</b>: Node.js, Express, TypeScript</li>
  <li><b>Database</b>: MongoDB</li>
  <li><b>Object Data Modeling</b>: Mongoose</li>
  <li><b>Tools</b>: Postman, MongoDB Atlas, MongoDB Compass, Google Cloud Platform, Cloudinary</li>
  <li><b>Deploy</b>: Vercel</li>
  <li><b>Architecture</b>:
    <ul>
      <li><b>Module Type</b>: ECMAScript Modules (ESM)</li>
      <li><b>REST API</b></li>
      <li><b>Authentication</b>:
        <ul>   
          <li><b>Methods</b>:
            <ol type="1">
              <li><b>Register / Login</b>: using user credentials</li>
              <li><b>Google OAuth</b>: using user Google account</li>
            </ol>
          </li>
          <li><b>Upon successful authentication</b>:
            <ul>
              <li><b>Token pair generation</b>:
                <ul>
                  <li><b>Access Token</b>: JSON Web Token (JWT) with a lifespan of 15 minutes</li>
                  <li><b>Refresh Token</b>: Random bytes token, created using crypto, securely stored in the database</li>
                </ul>
              </li>
              <li><b>Server-Side Cookies Response</b>: 
                <ul>
                  <li><b>accessToken Cookie</b>: valid for 15 minutes</li>
                  <li><b>refreshToken Cookie</b>: valid for 24 hours</li>
                </ul>
              </li>
            </ul>
          </li>
        </ul>
      </li>
      <li><b>Authorization</b>: In order to access protected routes and private resources, requests must pass through an authorization layer represented by the jwtAuthMiddleware.</li>
      <li><b>Middleware</b>:
        <ul>
          <li><b>jwtAuthMiddleware</b>: 
            <ul>
              <li>Uses the "passport-jwt strategy" to decode the JSON Web Token (JWT) from the accessToken Cookie and search for the user in the database.</li>
              <li>If the accessToken is expired, the middleware attempts to use the refreshToken from the refreshToken Cookie, to find the user.</li>
              <li>If the user is found using the refreshToken, the token pair is regenerated, and access to the route is granted.</li>
              <li>If neither accessToken nor refreshToken are valid, access to the route is denied, and a 401 response is sent.</li>
            </ul>
          </li>
          <li><b>googleAuthMiddleware</b>: 
            <ul>
              <li>Uses the "passport-google-oauth20 strategy" to handle user authentication through Google.</li>
              <li>Searches for the user in the database based on the information received from Google.</li>
              <li>If the user doesn't exist, it creates a new user with the provided details.</li>
            </ul>
          </li>
          <li><b>cookieParserMiddleware</b>: Uses the "cookie-parser" library to parse cookies from client requests.</li>    
          <li><b>validateTokenMiddleware</b>: Checks the validation token, which can be used in two scenarios: Google authentication process and password reset procedure.</li>
          <li><b>multipartMiddleware</b>: Uses the "multer" library to manage multipart/form-data.</li>
          <li><b>corsMiddleware</b>: Uses the "cors" library to allow secure cross-origin requests exclusively from the client's application.</li>
          <li><b>loggerMiddleware</b>: Uses the "morgan" library to provide logging for HTTP requests and responses, enhancing debugging and monitoring processes.</li>
          <li><b>missingRouteMiddleware</b>: Handles missing routes by sending a 404 response with a "API route not found" message.</li>
          <li><b>errorMiddleware</b>: Captures all errors from the code and sends appropriate responses based on the error type.</li>
        </ul>
      </li>
    </ul>
  </li>

  <li><b>Other Details</b>:
    <ul>
      <li><b>Type Safety</b>: Ensured by TypeScript for a more reliable and maintainable codebase.</li>
      <li><b>Linting</b>: ESLint Configuration for a clean and robust codebase.</li>
      <li><b>Environment Variables</b>: Managed using Dotenv for secure configuration of sensitive information.</li>
      <li><b>Nodemon</b>: Automatically restarts the server upon detecting changes in source files, enhancing development experience.</li>
      <li><b>Bcrypt</b>: Provides secure hashing of passwords to protect user credentials.</li>
      <li><b>Cloudinary</b>: Ensures the secure upload and storage of user profile pictures in the cloud, generating a link to the resource.</li>
      <li><b>Nodemailer</b>: Sends confirmation emails to users after receiving support inquiries and handles sending password reset links.</li>
      <li><b>Swagger</b>: Used to document and test the API endpoints interactively.</li>
      <li><b>Data Validation</b>:
        <ul>
          <li><b>Request Validation</b>: Uses Joi library as the first layer to validate received data, ensuring it meets the required format and constraints.</li>
          <li><b>Database Validation</b>: Uses Mongoose Schema validation as the second layer to enforce data integrity and constraints when storing data in MongoDB.</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>
