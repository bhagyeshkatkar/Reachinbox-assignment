
## Assignment: Associate Frontend Engineer


### **Overview**

**ReachInbox** is an innovative AI-powered platform that revolutionizes the cold outreach process for businesses. Serving as an all-in-one solution, ReachInbox seamlessly identifies, enriches, and engages high-intent leads through multi-channel outreach, including Twitter, LinkedIn, email, and phone. 

With just a single prompt, ReachInbox initiates a comprehensive outreach process—prospecting and verifying leads, crafting personalized outreach sequences, and delivering real-time notifications for responsive prospects. Think of it as an AI-driven growth team continuously working to generate top-tier leads for your business. ReachInbox is not just a tool; it's your dedicated partner in growth.

### **Technologies**

- **React.js**: Utilized for building a dynamic and responsive user interface.
- **Tailwind CSS**: Employed for styling the application with utility-first CSS, ensuring a sleek and modern design.
- **Vite.js**: A fast build tool that optimizes both development and production environments.
- **TypeScript**: Integrated to provide static typing, enhancing code quality and ensuring type safety.
- **Vercel**: Deployed on Vercel for hosting and continuous deployment, ensuring seamless and reliable access.

## Features

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


### **Preview**

**login**
![image](https://github.com/user-attachments/assets/11172e5b-3fbd-46e1-909a-e9e9e8657b73)

**OneBox**
![image](https://github.com/user-attachments/assets/367b19d4-b328-42b9-be87-710941914797)

**MailList**
![image](https://github.com/user-attachments/assets/981fa4f6-5d70-40a9-b51a-b7986247aef6)

**reply section**
![image](https://github.com/user-attachments/assets/95f99725-eea1-4072-9500-d124d40c0b95)

**Delete Popup**
![image](https://github.com/user-attachments/assets/6143a1ab-c81f-41fa-80e8-4de886782fd5)

