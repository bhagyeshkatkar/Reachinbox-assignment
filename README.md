# ReachInbox Frontend Assignment
## Overview
Welcome to the ReachInbox frontend assignment repository. This project showcases the implementation of a dynamic, responsive outbound marketing system using ReactJS, NextJS, Tailwind CSS, and other modern web technologies. As part of the assignment for the Associate - Frontend Engineer position at ReachInbox.ai, this repository includes features such as dynamic data handling, API integration, Google authentication, and pixel-perfect design.

# Features 
1. **User Authentication**: Implemented login page using the provided design.
2. **Email Viewing**: Fetch and display emails in the OneBox screen after login.
3. **API Integration**:
   - GET /onebox/list
   - GET /onebox/:thread_id
   - DELETE /onebox/:thread_id
4. **Keyboard Shortcuts**:
   - "D" to delete an email
   - "R" to open the reply box
5. **Custom Text Editor**: Added custom buttons like "SAVE" and "Variables" in the text editor.
6. **Reply Functionality**: Implemented sending replies using the API.
   - POST /reply/:thread_id
     ```json
     {
       "from": "email",
       "to": "email",
       "subject": "",
       "body": ""
     }
     ```
7. **Light and Dark Mode**: Supports both themes.

### **Technologies**

- **React.js**: Utilized for building a dynamic and responsive user interface.
- **Tailwind CSS**: Employed for styling the application with utility-first CSS, ensuring a sleek and modern design.
- **Vite.js**: A fast build tool that optimizes both development and production environments.
- **TypeScript**: Integrated to provide static typing, enhancing code quality and ensuring type safety.
- **Vercel**: Deployed on Vercel for hosting and continuous deployment, ensuring seamless and reliable access.

### **Preview**
![image](https://github.com/user-attachments/assets/11172e5b-3fbd-46e1-909a-e9e9e8657b73)
