Workflows:
1. CPU Information Workflow:

    Start: You tell the system, "Hey, tell me about the CPU."
   
    Process: The system checks and provides information about the CPU.
   
    End: You see the details about your computer's CPU.

3. Memory Information Workflow:

    Start: You say, "What about the memory of my computer?"
   
    Process: The system checks and gives you information about the memory (RAM).
   
    End: You get to see details about how your computer's memory is being used.

5. User Management Workflows:

   Create User:
   Start: You decide, "I want to add a new user."
   
   Process: The system creates a new user for you.
      
   End: The system tells you whether it was successful or if there was an issue.

    List Users:
   Start: You ask, "Who are the users on this system?"
   
   Process: The system shows you a list of all the regular users.
   
   End: You see the list.

    List Sudo Users:
   Start: You inquire, "Who has special permissions on this system?"

   Process: The system shows you a list of users with special permissions.
   
   End: You get to see that list.

7. File Information Workflow:

    Start: You command, "Tell me about this file."
   
    Process: The system checks the file and offers options like size, permissions, owner, and last modified time.
   
    End: You receive specific information based on your choice.

Application Architecture:

  Components:
        There's a tool or script called internsctl.
        It interacts with various tools on your computer, like checking the CPU or creating users.

Interactions:
  You use internsctl by typing commands to ask questions or perform actions.
        
  The script talks to other tools on your computer to get the information or do what you asked.

  Dependency:
        internsctl relies on existing tools on your computer to do its job. It's like asking for help from different experts when needed.

  User Interface:
        When you use internsctl, it's like having a conversation with your computer through typed commands.
