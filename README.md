## Flutter Hands-On Technical Test

### Objective:
Evaluate the candidate's proficiency in UI design implementation, state management using Bloc/Cubit, lazy loading (infinite scroll), API integration, and overall Flutter coding practices.

---

### Duration:
**2 hours**

---

### Instructions:
- **Internet usage** is allowed to refer to documentation only.
- **No copy-pasting** code from existing projects or external resources.
- Using ChatGPT or any other Generative AI tools is **strictly prohibited**.
- Commit your final code to a **public GitHub repository** and share the link with the invigilator.

---

### Test Components:

### 1) Login Page Implementation (Design Mimicry)
- Design mock-up provided below must be accurately recreated.
- Validate candidate's skill in translating designs into Flutter UI.

**Design Image:**

![image](https://github.com/user-attachments/assets/c2a413e3-c067-4beb-9c65-88753620dd51)


**Elements:**
- Logo/Image
- Username field
- Password field
- Login Button
- Social Buttons
- Login/Sign up Tab
- Simple Navigation (no authentication logic)

---

### 2) Navigation to Home Screen
- Implement basic navigation from the login button click to the Home screen.
- No API call required at login.

---

### 3) Home Screen with Infinite Scroll & API Integration

**Requirements:**
- Fetch and display dog images from:
  ```
  https://api.thedogapi.com/v1/images/search?limit=100&page=0&order=Desc
  ```
- Implement **lazy loading (pagination/infinite scroll)**. Load additional images as the user scrolls down.
- Display a loading indicator when fetching new data.
- Implement state management using **Bloc and Cubit**.

**UI Expectations:**
- Grid or List-based infinite scrolling layout
- Smooth scroll experience
- Proper error handling (show simple messages if API fails)

---

### Evaluation Criteria:
- Accuracy of UI design implementation
- Correctness and effectiveness of Bloc/Cubit usage
- Implementation of lazy loading
- Code readability and structure
- Proper state management
- Git commit practices

---

### Submission:
- Ensure your GitHub repo is public.
- Provide the repository link to the invigilator at the end of the session.

---

### Good luck!

