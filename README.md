# Doctor Appointment System in C++

This is a simple console-based Doctor Appointment System implemented in C++. The system allows users to book and check existing appointments with a doctor. It provides a basic menu-driven interface for interacting with the system.

## How to Use

1. **Book Appointment**: Users can book an appointment with the doctor by selecting an available time slot. If a slot is already booked, the system will not allow another booking for that time.

2. **Check Existing Appointment**: Users can check the existing appointments and see the available time slots.

3. **Exit**: To exit the program, you can choose this option. It will ask for confirmation before exiting.

## How to Compile and Run

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/swetamishra123/Doctor-Appointement-cpp.git
   ```

2. Navigate to the project directory:

   ```
   cd Doctor-Appointement-cpp
   ```

3. Compile the code:

   ```
   g++ -o doctor_appointment main.cpp
   ```

4. Run the program:

   ```
   ./doctor_appointment
   ```

## Features

- Book appointments for various hours of the day.
- View existing appointments and available time slots.
- Simple and user-friendly command-line interface.
- Basic error handling for invalid input.

## Output-Flow


1. **Doctor Appointment System**: This is the title of the system, indicating what the program does.

2. **Menu Options**:
   - **1. Book Appointment**: This option allows you to book an appointment with the doctor.
   - **2. Check Existing Appointment**: This option allows you to check existing appointments.
   - **0. Exit**: This option allows you to exit the program.

3. **Enter your choice**: You are prompted to enter your choice by typing a number (1, 2, or 0) and pressing Enter.

4. **Book Appointment**:
   - If you select option 1, it will display available time slots, indicating which slots are available and which are booked.
   - You can enter a choice by typing a letter (A to Z) corresponding to the time slot you want to book.
   - If you select a time slot that is already booked, you'll receive an error message, and you need to choose a different time.

5. **Check Existing Appointment**:
   - If you select option 2, it will show the summary of appointments. It lists available and booked time slots.

6. **Exit Confirmation**:
   - If you select option 0 (Exit), the program asks for confirmation by typing 'y' for yes or 'n' for no. You can exit by typing 'y' or continue using the system by typing 'n'.

7. **Invalid Choices**:
   - If you make an invalid selection or input, you'll receive an error message and be prompted to enter a valid choice.

8. **Continuation**:
   - After performing any action (booking an appointment, checking appointments, etc.), you are prompted to press any key to continue. This allows you to return to the main menu.

## Look-Alike
```plaintext
 ----- Book Your Appointment ----
```

This line indicates that you are in the process of booking an appointment.

```plaintext
 ----- Availbale slots ----
```

This line shows the available time slots for booking.

```plaintext
 Appointment Summary by hours:
```

This section is providing a summary of appointments by hours. It will show whether a particular time slot is available or booked.

```plaintext
 A-> 09 - Available
 B->10 - Available
 C->11 - Available
 D->12 - Available
 E->13 - Available
 F->14 - Available
 G->15 - Available
 H->16 - Available
 I->17 - Available
 J->18 - Available
 K->19 - Available
 L->20 - Available
 M->21 - Booked
```

This part of the output is a summary of available time slots. Each letter from 'A' to 'M' represents an available hour. The arrow '->' is used to separate the letter from the corresponding hour. If it says "Available" next to a time slot, it means that appointment slot is currently open for booking. However, in this example, it shows that the time slot 'M' (which corresponds to 21:00) is already booked, as it says "Booked."

Here's an example of the data stored in "appointment.dat" based on the output:

- 'M:SWETA' means that the appointment slot 'M' (21:00) is booked by 'SWETA.'
- 'E:SNEHA' would indicate that the appointment slot 'E' (13:00) is booked by 'SNEHA.'
- 'K:Rajeev' would signify that the appointment slot 'K' (19:00) is booked by 'Rajeev.'

The format appears to be a single character representing the appointment slot followed by a colon and the name of the person who booked that slot.

In this example, you can see that the appointment slot 'M' is already booked, which is why it is labeled as "Booked" in the summary. The user is prompted to select an available slot for booking. If they select 'M' again, it would display an error message indicating that the slot is already booked, and they would need to choose a different available time slot.

## Contributing

If you want to contribute to this project, feel free to fork the repository and submit pull requests with your improvements and changes.

## License

This project is open-source and available under the [MIT License](LICENSE). You are free to use and modify the code as needed.

## About the Author

This Doctor Appointment System project was created bswetamishra123. If you have any questions or suggestions, please feel free to contact me at [swetamishra@gmail.com](swetamishra603@gmail.com)

Enjoy using the Doctor Appointment System!
