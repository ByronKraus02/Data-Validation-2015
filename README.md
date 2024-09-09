# GRADE 12 Data Validation Project (2020)

This project is a graphical user interface (GUI) application designed to validate various types of user input data, such as ID numbers, ages, dates, and booking types. The focus was on testing the data for presence, data type, length, and range to ensure that only valid inputs are processed.

### Key Components:
1. **GUI**: 
   - The graphical interface consists of text fields for ID number, age, and date, as well as radio buttons for selecting the booking type (SmartID or Passport). There are checkboxes for validation feedback, which indicate whether the input meets the validation criteria.
  
2. **Test Data**:
   - **Standard Data**: Input that meets the validation requirements.
   - **Extreme Data**: Values at the limits of acceptable ranges (e.g., very old dates or large numbers).
   - **Abnormal Data**: Invalid inputs that do not meet the validation criteria (e.g., non-numeric values in the ID field).

3. **Data Validation Types**:
   - **Presence Check**: Ensures that fields are not left empty.
   - **Data Type Check**: Verifies that the input matches the required format (e.g., numeric data for age and ID).
   - **Length Check**: Confirms that the ID and date fields have the correct number of characters.
   - **Range Check**: Ensures that the entered date falls within an acceptable range (e.g., months between 1 and 12).

4. **Explanation of Fields, Types, and Components**:
   - Each field in the application is accompanied by a validation type to ensure proper user input. For example, the ID Number field checks for presence, data type, and length to make sure it is a valid 13-digit number.

5. **Code**:
   - The backend code is implemented in Java using the Swing framework for the GUI. The logic for data validation is embedded in the `EnterButtonActionPerformed` method, which checks for valid ID numbers, ages, dates, and the selection of a booking type.
