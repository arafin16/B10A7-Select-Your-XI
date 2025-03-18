@@ -1,8 +1,22 @@
 # React + Vite
  # Dream BPL 11 
   This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules. 
   ## 📖 Overview
    Dream BPL 11 is a React-based application that allows users to select and manage cricket players for their dream team. Users can view available players, select their favorites, and keep track of their chosen team in a visually appealing interface.
 ## 🚀 Technologies Used 
  - React 
  - useState 
  - useEffect 
   ## ✨ Key Features 
   1. **Dynamic Player Selection**:  
      - Users can toggle between "Available" and "Selected" players with intuitive buttons. The "Selected" button displays the count of selected players, updating in real-time. 
   2. **Robust Validation on Player Selection**:  
      - When a user clicks "Choose Player," the app checks if the player has already been selected. If so, an alert is displayed to inform the user ("Player already selected"), and the selection is terminated.  
        - Additionally, if the user attempts to select more than six players, an alert will notify them that they have reached the maximum limit, preventing further selection. 
   3. **Intuitive Selection Process**:   
     - Upon clicking the "Choose Player" button, the application checks if the user has sufficient coins. If not, an alert is displayed. Selected players are added to a dedicated list with the option to remove them. 
   