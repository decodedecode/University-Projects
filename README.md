### README for Medical Result Analysis and Suggestions Program

#### Overview
This C program, developed by **Sarthak Shukla**, is designed to analyze medical results and provide suggestions based on the user's input. The program focuses on three main areas:
1. **Blood Pressure Analysis**
2. **Lipid Profile Analysis**
3. **Diabetes Analysis**

The program takes user inputs for specific medical parameters and provides feedback on whether the values are within the normal range. If the values are outside the normal range, the program offers suggestions and lifestyle changes to help manage the condition.

---

#### Features
1. **Blood Pressure Analysis**:
   - Takes input for **Systolic Blood Pressure (SBP)** and **Diastolic Blood Pressure (DBP)**.
   - Provides feedback on whether the blood pressure is normal, low (hypotension), or high (hypertension).
   - Offers suggestions for maintaining or improving blood pressure levels.

2. **Lipid Profile Analysis**:
   - Takes input for **Triglycerides**, **Total Cholesterol**, **HDL (Good Cholesterol)**, **LDL (Bad Cholesterol)**, and **VLDL Cholesterol**.
   - Checks if the values are within the normal range.
   - Provides recommendations for managing lipid levels if they are outside the desired range.

3. **Diabetes Analysis**:
   - Takes input for **Blood Sugar (Fasting)**, **Blood Sugar (Postprandial)**, and **Blood Sugar (Random)**.
   - Evaluates if the blood sugar levels are within the normal range.
   - Offers lifestyle and dietary suggestions to manage blood sugar levels.

---

#### How to Use
1. **Compile the Program**:
   - Use a C compiler (e.g., GCC) to compile the program:
     ```bash
     gcc medical_analysis.c -o medical_analysis
     ```

2. **Run the Program**:
   - Execute the compiled program:
     ```bash
     ./medical_analysis
     ```

3. **Follow the Prompts**:
   - The program will display a menu with three options:
     - **1. Blood Pressure**
     - **2. Lipid Profile**
     - **3. Diabetes**
   - Enter the number corresponding to the analysis you want to perform.

4. **Input Your Medical Data**:
   - Provide the required medical values when prompted.

5. **View Results and Suggestions**:
   - The program will analyze the input and provide feedback along with suggestions for maintaining or improving your health.

---

#### Example Input/Output

**Example 1: Blood Pressure Analysis**
```
What would you like to analyse about :
1. Blood Pressure
2. Lipid Profile
3. Diabetes
(for ex. Type '1' for Blood Pressure)   :  1

You Chose 1. BLOOD PRESSURE
Please Enter your Systolic Blood Pressure   :  130
PRE-HYPERTENTION
Your Blood pressure is quite high
Here's what you can do :
1. Lose extra pounds and watch your waistline.
2. Exercise regularly.
3. Eat a healthy diet.
4. Reduce salt sodium in your diet.
5. Limit alcohol.
6. Quit smoking.
7. Get a good night's sleep.
8. Reduce stress.

Please Enter your Diastolic Blood Pressure  :  85
DBP-HYPERTENTION
1. Increase activity and exercise more
2. Lose weight if you're overweight
3. Cut back on sugar and refined carbohydrates
4. Eat more potassium and less sodium
5. Eat garlic or take garlic extract supplements
6. Eat some dark chocolate
```

**Example 2: Lipid Profile Analysis**
```
What would you like to analyse about :
1. Blood Pressure
2. Lipid Profile
3. Diabetes
(for ex. Type '1' for Blood Pressure)   :  2

You Chose 2. Lipid Profile
Enter your units (Mg/d) :
1. Tryglyceride :  170
Your Tryglyceride level is inadequate
8 Ways to Control Your Triglycerides (and Cholesterol) With Lifestyle Changes
1. Avoid excess sugar
2. Resist refined foods
3. Add more fiber to your diet
4. Choose healthy fats over saturated fats.
5. Know the dangers of trans fats
6. Cut back on alcohol
7. Exercise
8. Control your weight.
```

**Example 3: Diabetes Analysis**
```
What would you like to analyse about :
1. Blood Pressure
2. Lipid Profile
3. Diabetes
(for ex. Type '1' for Blood Pressure)   :  3

You chose 3. Diabetes
Enter your units (Mg/d) :
1. Blood Sugar (Fasting) :  130
Your Sugar value is not desirable
This article looks at 12 simple things you can do to prevent blood sugar spikes.
1. Go low-carb.
2. Eat fewer refined carbs.
3. Reduce your sugar intake.
4. Keep a healthy weight.
5. Exercise more.
6. Eat more fiber.
7. Drink more water.
8. Introduce some vinegar into your diet.
```

---

#### Notes
- The program is designed for educational purposes and should not replace professional medical advice.
- Ensure that the input values are accurate for meaningful results.
- The program handles invalid inputs by displaying an "INVALID RESPONSE" message.

---

#### Dependencies
- Standard C libraries:
  - `stdio.h`
  - `conio.h`
  - `string.h`
  - `stdlib.h`

---

#### Author
- **Sarthak Shukla**
- Enrollment No: 2101112038
- Title of the Paper: End Semester Project 1
- Paper Code: SDL-107

---

#### License
This project is open-source and free to use. Feel free to modify and distribute it as needed.

---

Thank you for using the Medical Result Analysis and Suggestions Program! Stay healthy! 😊
