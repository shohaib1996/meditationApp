# 📘 Meditation App — User Stories

This document outlines all user stories for the Meditation App, covering authentication, homepage experience, detailed exercise screens, favorites, reminders, sharing, logout, and settings. These stories follow Agile best practices and guide the app’s development toward a smooth, personalized meditation experience.

---

## 🧩 User Story Template

**Title:**  
As a `<user role>`, I want to `<action>` so that `<goal or benefit>`.

**Acceptance Criteria:**  
1.  
2.  
3.  

**Story Points:** X

---

# ✅ User Stories

---

## 🔐 1. Login & Registration

### **User Story 1: Register an Account**
As a user, I want to register by entering my username, email, and password, so that I can create an account.

**Acceptance Criteria:**
- Users can input valid details and click **Sign Up**.
- Error messages appear for missing or invalid input.
- User details are stored in local storage.

---

### **User Story 2: Log Into Account**
As a user, I want to log in using my email and password, so that I can access my account.

**Acceptance Criteria:**
- Users can log in with correct credentials.
- Users are redirected to the dashboard.
- Error message is shown for incorrect login.

---

### **User Story 3: Input Validation Feedback**
As a user, I want to receive feedback when attempting to sign up or log in without entering details, so that I know what to fix.

**Acceptance Criteria:**
- Missing fields trigger visible error messages.

---

## 🏠 2. Homepage

### **User Story 4: Personalized Greeting**
As a user, I want a personalized greeting with my name, so that I feel welcomed.

**Acceptance Criteria:**
- Display “Hello, [username] — Find your perfect meditation.”

---

### **User Story 5: Popular Meditations**
As a user, I want to see popular meditation cards, so that I can explore quickly.

**Acceptance Criteria:**
- Cards show image, title, description, category, and duration.

---

### **User Story 6: Daily Featured Meditation**
As a user, I want a highlighted meditation each day, so that I can try something new.

**Acceptance Criteria:**
- A dedicated section displays one featured meditation.

---

### **User Story 7: Intuitive Navigation**
As a user, I want navigation icons, so that I can move around easily.

**Acceptance Criteria:**
- Logo (top left) and Settings icon (top right) are visible.

---

## 📄 3. Exercise Details Page

### **User Story 8: About Section**
As a user, I want an "About" section, so that I know the purpose of the exercise.

**Acceptance Criteria:**
- Shows a short description explaining benefits.

---

### **User Story 9: Instructions**
As a user, I want an "Instructions" section, so that I can perform the exercise correctly.

**Acceptance Criteria:**
- Step-by-step posture & breathing instructions are provided.

---

### **User Story 10: Add to Favorites**
As a user, I want an “Add to Favorites” button, so that I can save exercises.

**Acceptance Criteria:**
- Prominent button at bottom of page.

---

### **User Story 11: Navigation Icons**
As a user, I want share/back icons, so that I can share or go back easily.

**Acceptance Criteria:**
- Back icon & share icon visible at top.

---

## ❤️ 4. Favorites System

### **User Story 12: Add to Favorites**
As a user, I want to add exercises to Favorites, so that I can access them easily.

**Acceptance Criteria:**
- Heart icon (outlined by default).
- Tapping adds to favorites and fills heart.
- Button text toggles between Add/Remove.

---

### **User Story 13: Remove from Favorites**
As a user, I want to remove items from Favorites, so that I can manage my list.

**Acceptance Criteria:**
- “Remove from Favorites” button shown when item is saved.
- Tapping removes from list and reverts icon.

---

### **User Story 14: View Favorites**
As a user, I want a Favorites screen, so that I can browse saved items.

**Acceptance Criteria:**
- Shows all saved items with title, category, and duration.
- Tapping an item opens its detail page.

---

## ⏰ 5. Daily Reminders

### **User Story 15: Calendar Navigation**
As a user, I want to view a monthly calendar, so that I can select dates.

**Acceptance Criteria:**
- Visible current month.
- Arrows to navigate months.

---

### **User Story 16: Select Date & Time**
As a user, I want to choose a date and time, so that I can schedule reminders.

**Acceptance Criteria:**
- Default “Selected Date: None.”
- User can select date + adjust time.

---

### **User Story 17: Add Reminder**
As a user, I want to add a reminder, so that I remember to meditate.

**Acceptance Criteria:**
- “Add Reminder” button schedules the chosen time/date.

---

### **User Story 18: View/Delete Reminders**
As a user, I want to see and delete reminders, so that I can manage them.

**Acceptance Criteria:**
- List of reminders displayed.
- Red Delete button removes them.

---

## 📤 6. Sharing

### **User Story 19: Share Exercises**
As a user, I want to share exercises, so that I can recommend them to others.

**Acceptance Criteria:**
- Share icon visible on detail page.
- Supports multiple platforms (email, messaging, social).

---

## 🚪 7. Logout

### **User Story 20: Logout**
As a user, I want a visible logout button, so that I can exit securely.

**Acceptance Criteria:**
- Logout button is clearly visible.
- Redirects user to login page.
- Clears user session data.

---

## 🎨 8. Settings (Theme Toggle)

### **User Story 21: Toggle Light/Dark Mode**
As a user, I want to switch between light and dark themes, so that I can personalize my experience.

**Acceptance Criteria:**
- Theme toggle switch available in settings.
- Theme switches instantly without restart.

---

# 🎉 Conclusion

These user stories define the core functionality of the Meditation App and help ensure a smooth, personalized, and user-friendly experience. They guide development, testing, and design decisions across the entire application.
