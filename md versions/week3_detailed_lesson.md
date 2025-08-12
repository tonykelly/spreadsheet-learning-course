# Week 3: Basic Formulas - Detailed Lesson for Complete Beginners

## Learning Objectives:
By the end of this lesson, you will be able to:
- Understand formula structure and syntax in spreadsheets
- Create basic calculations using arithmetic operators (+, -, *, /, ^)
- Use cell references in formulas and understand how they work
- Copy formulas and understand how references change
- Identify and fix common formula errors

---

## Topic 1: Formula Fundamentals

### What is a Formula?
A formula is a calculation instruction that tells the spreadsheet how to process your data. Think of it as a recipe that Excel follows to get a result. Every formula in Excel **must start with an equals sign (=)**.

### Visual Reference Screenshots:
- [Excel Formula Structure](https://support.microsoft.com/en-us/office/overview-of-formulas-in-excel-ecfdc708-9162-49e8-b993-c311f47ca173) - Shows how formulas begin with = and their basic components
- [Formula Bar and Editing](https://excelx.com/formula/symbols/) - Demonstrates where formulas appear and how to edit them

### Why Do Formulas Start with "="?
The equals sign tells Excel "Hey, this isn't just data - this is a calculation you need to perform!" Without the equals sign, Excel treats your input as regular text.

**Example:**
- Typing `2+3` in a cell → Excel shows "2+3" as text
- Typing `=2+3` in a cell → Excel calculates and shows "5"

### Formula Components
Every formula can contain:
1. **The equals sign (=)** - Always comes first
2. **Values** - Numbers like 5, 100, 3.14
3. **Operators** - Symbols like +, -, *, /
4. **Cell references** - Like A1, B2, C5
5. **Functions** - Built-in calculations like SUM, AVERAGE

### Step-by-Step: Creating Your First Formula
1. **Click on an empty cell** (let's use cell C1)
2. **Type**: =5+3
3. **Press Enter**
4. **Result**: The cell shows "8" but the formula bar shows "=5+3"

**What happened?** Excel calculated 5+3 and displayed the result (8) in the cell, while keeping the formula visible in the formula bar.

### Formula Bar vs. Cell Display
- **Formula Bar**: Shows the actual formula (=5+3)
- **Cell**: Shows the calculated result (8)
- **To edit a formula**: Click the cell and look at the formula bar, or double-click the cell

### Step-by-Step: Understanding Formula Input
1. **Select cell D1**
2. **Type**: =10*2
3. **Before pressing Enter**, notice:
   - The formula appears in the formula bar
   - The cell shows the formula as you type
4. **Press Enter**
5. **Now notice**:
   - The cell shows the result (20)
   - The formula bar shows the formula (=10*2)

### Practice Exercise: Formula Basics
1. **In cell A1**: Type =7+3 (Result should be 10)
2. **In cell A2**: Type =15-6 (Result should be 9)  
3. **In cell A3**: Type =4*5 (Result should be 20)
4. **In cell A4**: Type =20/4 (Result should be 5)
5. **Click on each cell** and observe how the formula bar shows the calculation while the cell shows the result

---

## Topic 2: Arithmetic Operators

### The Five Basic Arithmetic Operators
Excel uses these symbols for mathematical operations:

| Operator | Operation | Example | Result |
|----------|-----------|---------|--------|
| + | Addition | =5+3 | 8 |
| - | Subtraction | =10-4 | 6 |
| * | Multiplication | =6*7 | 42 |
| / | Division | =15/3 | 5 |
| ^ | Exponentiation (Power) | =2^3 | 8 |

### Visual Reference Screenshots:
- [Excel Operators and Precedence](https://support.microsoft.com/en-us/office/calculation-operators-and-precedence-in-excel-48be406d-4975-4d31-b2b8-7af9e0e2878a) - Shows all operator types and how Excel processes them
- [Formula Symbols Guide](https://www.automateexcel.com/how-to/signs-symbols-mean-in-formulas/) - Comprehensive guide to formula symbols

### Important Notes About Operators:
- **Multiplication**: Use * (asterisk), not × (times symbol)
- **Division**: Use / (forward slash), not ÷ (division symbol) 
- **Exponentiation**: Use ^ (caret) for powers, like 2^3 = 8

### Order of Operations (PEMDAS/BODMAS)
Excel follows mathematical order of operations:
1. **P**arentheses first
2. **E**xponents (powers)
3. **M**ultiplication and **D**ivision (left to right)
4. **A**ddition and **S**ubtraction (left to right)

### Step-by-Step: Understanding Order of Operations
1. **In cell B1**: Type =2+3*4
2. **Press Enter** 
3. **Result**: 14 (not 20!)
4. **Why?** Excel calculates 3*4=12 first, then 2+12=14

**Now let's change the order:**
1. **In cell B2**: Type =(2+3)*4
2. **Press Enter**
3. **Result**: 20
4. **Why?** Parentheses force Excel to calculate 2+3=5 first, then 5*4=20

### Working with Percentages
The % operator automatically divides by 100:
- **=25%** gives 0.25
- **=25/100** also gives 0.25
- **To calculate 25% of 200**: =200*25% or =200*0.25

### Step-by-Step: Percentage Calculations
1. **In cell C1**: Type =200*25%
2. **Press Enter** (Result: 50)
3. **In cell C2**: Type =200*0.25
4. **Press Enter** (Result: 50 - same answer!)

### Complex Formula Example
Let's create a formula that calculates the total cost including tax:
- Base price: $100
- Tax rate: 8.5%
- Formula: Base price + (Base price × Tax rate)

**Step-by-Step:**
1. **In cell D1**: Type =100+(100*8.5%)
2. **Press Enter** (Result: 108.5)
3. **Alternative with parentheses**: =100*(1+8.5%) also gives 108.5

### Practice Exercise: Arithmetic Operations
**Create a simple calculator:**
1. **Cell E1**: =25+17 (Addition)
2. **Cell E2**: =100-35 (Subtraction)
3. **Cell E3**: =12*8 (Multiplication)
4. **Cell E4**: =144/12 (Division)
5. **Cell E5**: =3^4 (Exponentiation - 3 to the power of 4)
6. **Cell E6**: =(5+3)*2 (Order of operations)
7. **Cell E7**: =5+3*2 (Compare with E6)

**Check your results:**
- E1: 42
- E2: 65
- E3: 96
- E4: 12
- E5: 81
- E6: 16
- E7: 11

---

## Topic 3: Cell References in Formulas

### What are Cell References?
Instead of typing numbers directly into formulas, you can reference cells that contain numbers. This makes your spreadsheets dynamic - when the referenced cell changes, the formula result updates automatically.

### Visual Reference Screenshots:
- [Excel Cell References Tutorial](https://edu.gcfglobal.org/en/excelformulas/relative-and-absolute-cell-references/1/) - Shows how cell references work in formulas
- [Relative vs Absolute References](https://www.ablebits.com/office-addins-blog/relative-absolute-reference-excel/) - Demonstrates different types of cell references

### Basic Cell Reference Examples:
- **=A1** → Uses the value in cell A1
- **=A1+B1** → Adds the values in cells A1 and B1
- **=A1*B1** → Multiplies the values in cells A1 and B1

### Step-by-Step: Creating Formulas with Cell References
1. **Set up your data:**
   - A1: Type 10
   - B1: Type 5
   - C1: Type 3

2. **Create formulas using these cell references:**
   - D1: Type =A1+B1 (Result: 15)
   - D2: Type =A1*C1 (Result: 30)
   - D3: Type =B1/C1 (Result: 1.67)

3. **Test the dynamic nature:**
   - Change A1 to 20
   - Watch how D1 and D2 automatically update!

### Why Use Cell References Instead of Numbers?
**Example scenario**: Calculating sales tax

**Method 1 - Using numbers directly:**
- Formula: =100*0.085
- Problem: If tax rate changes, you must update every formula

**Method 2 - Using cell references:**
- A1: 100 (price)
- B1: 0.085 (tax rate)  
- Formula: =A1*B1
- Advantage: Change B1 once, all formulas update automatically

### Range References
You can reference multiple cells at once using ranges:
- **A1:A5** → Cells A1, A2, A3, A4, A5
- **B2:D2** → Cells B2, C2, D2
- **A1:C3** → A rectangular area from A1 to C3

### Step-by-Step: Understanding Range References
1. **Enter data in cells A1 through A5:**
   - A1: 10
   - A2: 20  
   - A3: 30
   - A4: 40
   - A5: 50

2. **Use a range in a formula:**
   - B1: Type =SUM(A1:A5)
   - Result: 150 (adds all values in the range)

### Pointing and Clicking to Create References
Instead of typing cell addresses, you can click on cells:

**Step-by-Step Method:**
1. **Click on cell C1**
2. **Type** =
3. **Click on cell A1** (Excel adds "A1" to your formula)
4. **Type** +
5. **Click on cell B1** (Excel adds "B1" to your formula)
6. **Press Enter**

Your formula is now =A1+B1 created without typing any cell addresses!

### Practice Exercise: Cell References
**Scenario**: Create a simple invoice calculator

1. **Set up your data:**
   - A1: "Item Price" (label)
   - A2: 25 (price of item)
   - B1: "Quantity" (label)
   - B2: 3 (number of items)
   - C1: "Tax Rate" (label)
   - C2: 0.075 (7.5% tax)

2. **Create calculations:**
   - D1: "Subtotal"
   - D2: =A2*B2 (Price × Quantity)
   - E1: "Tax Amount"  
   - E2: =D2*C2 (Subtotal × Tax Rate)
   - F1: "Total"
   - F2: =D2+E2 (Subtotal + Tax)

3. **Test the system:**
   - Change the quantity in B2 to 5
   - Watch all calculations update automatically!

---

## Topic 4: Formula Copying and Filling

### How Formula Copying Works
When you copy a formula to other cells, Excel automatically adjusts the cell references. This is called "relative referencing" and it's incredibly powerful for creating calculations across multiple rows or columns.

### Visual Reference Screenshots:
- [Relative Reference Examples](https://web.pdx.edu/~stipakb/CellRefs.htm) - Shows how references change when formulas are copied
- [Excel Fill Handle](https://www.w3schools.com/excel/excel_rel_ref.php) - Demonstrates the fill handle for copying formulas

### The Fill Handle Method
The easiest way to copy formulas is using the fill handle - a small square in the bottom-right corner of the selected cell.

### Step-by-Step: Using the Fill Handle
1. **Set up a multiplication table:**
   - A1: 1, A2: 2, A3: 3, A4: 4, A5: 5
   - B1: 10, C1: 20, D1: 30, E1: 40

2. **Create the first formula:**
   - B2: Type =A2*B1 (Result: 20)

3. **Copy using fill handle:**
   - Click on cell B2
   - Look for the small square in the bottom-right corner
   - Click and drag the fill handle across to column E
   - Release the mouse

4. **Check the results:**
   - B2: =A2*B1 (2*10 = 20)
   - C2: =A2*C1 (2*20 = 40)  
   - D2: =A2*D1 (2*30 = 60)
   - E2: =A2*E1 (2*40 = 80)

### How References Change When Copied
When you copy a formula horizontally (left to right):
- **Row numbers stay the same**
- **Column letters change** (B becomes C, C becomes D, etc.)

When you copy a formula vertically (up to down):
- **Column letters stay the same**
- **Row numbers change** (1 becomes 2, 2 becomes 3, etc.)

### Step-by-Step: Vertical Formula Copying
1. **Using the same setup, now copy downward:**
   - Select cell B2 (which contains =A2*B1)
   - Drag the fill handle down to row 5

2. **Check how the formula changed:**
   - B2: =A2*B1 (original)
   - B3: =A3*B1 (A2 changed to A3)
   - B4: =A4*B1 (A2 changed to A4)
   - B5: =A5*B1 (A2 changed to A5)

### Copy and Paste Method
Alternative to fill handle:
1. **Select the cell** with the formula
2. **Copy**: Ctrl+C
3. **Select the destination** cells
4. **Paste**: Ctrl+V

### Understanding Formula Pattern Recognition
Excel is smart about recognizing patterns. When you select multiple cells and drag, Excel extends the pattern:

**Example:**
1. **A1**: Type =B1*2
2. **A2**: Type =B2*2  
3. **Select both A1 and A2**
4. **Drag down** - Excel continues the pattern: =B3*2, =B4*2, etc.

### Practice Exercise: Formula Copying
**Create a sales commission calculator:**

1. **Set up the data:**
   - A1: "Salesperson", B1: "Sales Amount", C1: "Commission Rate", D1: "Commission Earned"
   - A2: "John", B2: 5000, C2: 0.05
   - A3: "Sarah", B3: 7500, C3: 0.05
   - A4: "Mike", B4: 6200, C4: 0.05

2. **Create the formula:**
   - D2: =B2*C2 (Sales × Commission Rate)

3. **Copy the formula:**
   - Select D2
   - Use fill handle to copy to D3 and D4
   - Verify the formulas adjusted correctly:
     - D3: =B3*C3
     - D4: =B4*C4

**Results should be:**
- D2: 250 (5000 × 0.05)
- D3: 375 (7500 × 0.05)  
- D4: 310 (6200 × 0.05)

---

## Topic 5: Common Formula Errors

### Understanding Formula Errors
Excel displays error messages when formulas can't be calculated. These errors help you identify and fix problems. Each error type tells you what went wrong.

### Visual Reference Screenshots:
- [Excel Formula Errors Guide](https://support.microsoft.com/en-us/office/how-to-avoid-broken-formulas-in-excel-8309381d-33e8-42f6-b889-84ef6df1d586) - Shows all error types and their meanings
- [DIV/0 Error Examples](https://exceljet.net/formulas/how-to-fix-the-div0-error) - Demonstrates division by zero errors

### The Most Common Formula Errors

#### 1. #DIV/0! Error (Division by Zero)
**What it means**: You're trying to divide by zero or an empty cell
**Common causes**:
- Dividing by zero: =10/0
- Dividing by empty cell: =A1/B1 where B1 is empty
- Formula references another cell with #DIV/0! error

**Step-by-Step: Creating and Fixing #DIV/0! Error**
1. **Create the error:**
   - A1: Type 10
   - B1: Leave empty
   - C1: Type =A1/B1 (Results in #DIV/0!)

2. **Fix the error:**
   - B1: Type 2
   - C1 now shows: 5

#### 2. #VALUE! Error (Wrong Data Type)
**What it means**: Formula expects numbers but finds text
**Common causes**:
- Adding numbers to text: ="Hello"+5
- Using text in math operations: =A1*B1 where A1 contains "abc"

**Step-by-Step: Creating and Fixing #VALUE! Error**
1. **Create the error:**
   - A1: Type "Hello"
   - B1: Type 5
   - C1: Type =A1+B1 (Results in #VALUE!)

2. **Fix the error:**
   - A1: Change to 10
   - C1 now shows: 15

#### 3. #REF! Error (Invalid Reference)
**What it means**: Formula refers to cells that don't exist or were deleted
**Common causes**:
- Deleting cells that formulas reference
- Copying formulas to locations where references become invalid

**Step-by-Step: Understanding #REF! Error**
1. **Set up the scenario:**
   - A1: Type 5
   - B1: Type 3  
   - C1: Type =A1+B1 (Shows 8)

2. **Create the error:**
   - Delete column A (right-click column A header → Delete)
   - C1 now shows: =#REF!+B1

3. **Fix the error:**
   - Edit the formula to use valid cell references

#### 4. #NAME? Error (Unrecognized Name)
**What it means**: Excel doesn't recognize something in your formula
**Common causes**:
- Misspelled function names: =SUMM(A1:A5) instead of =SUM(A1:A5)
- Missing quotes around text: =IF(A1=Hello,"Yes","No") should be =IF(A1="Hello","Yes","No")

**Step-by-Step: Creating and Fixing #NAME? Error**
1. **Create the error:**
   - A1: Type =SUMM(1,2,3) (Results in #NAME?)

2. **Fix the error:**
   - A1: Change to =SUM(1,2,3) (Shows 6)

### Error Prevention Strategies

#### 1. Check Your Data Types
- Make sure cells contain the expected data (numbers for math, text for text operations)
- Use the VALUE() function to convert text numbers to actual numbers

#### 2. Handle Division Carefully
- Always check that denominators aren't zero
- Use IF statements to test before dividing: =IF(B1=0,"Cannot divide by zero",A1/B1)

#### 3. Double-Check Cell References
- Make sure referenced cells exist
- Be careful when deleting rows or columns
- Use absolute references when needed (covered in advanced topics)

### Using IFERROR to Handle Errors Gracefully
The IFERROR function lets you show custom messages instead of error codes:

**Syntax**: =IFERROR(formula, value_if_error)

**Step-by-Step: Using IFERROR**
1. **Instead of**: =A1/B1
2. **Use**: =IFERROR(A1/B1,"Cannot calculate")
3. **Result**: Shows "Cannot calculate" instead of #DIV/0! when B1 is zero

### Practice Exercise: Error Handling
**Create an error-proof calculator:**

1. **Set up test data:**
   - A1: 10, B1: 2, C1: 0, D1: "Hello"

2. **Create formulas that will cause errors:**
   - E1: =A1/C1 (Division by zero)
   - E2: =A1+D1 (Adding number to text)

3. **Fix with IFERROR:**
   - F1: =IFERROR(A1/C1,"Error: Division by zero")
   - F2: =IFERROR(A1+D1,"Error: Invalid data type")

4. **Test different scenarios:**
   - Change C1 to 5 and see F1 update to show 2
   - Change D1 to 5 and see F2 update to show 15

---

## Comprehensive Practice Exercise: Personal Budget Calculator

Now let's combine all Week 3 concepts into one meaningful project.

### Project Overview:
Create a monthly budget calculator that demonstrates formulas, cell references, copying, and error handling.

### Step 1: Set Up Your Data Structure
1. **Create column headers in row 1:**
   - A1: "Category"
   - B1: "Budgeted Amount"  
   - C1: "Actual Amount"
   - D1: "Difference"
   - E1: "Percentage Used"

### Step 2: Enter Budget Categories
2. **Enter categories in column A:**
   - A2: "Housing"
   - A3: "Food"
   - A4: "Transportation"
   - A5: "Entertainment"
   - A6: "Savings"
   - A8: "TOTALS"

### Step 3: Enter Budget and Actual Amounts
3. **Enter budgeted amounts in column B:**
   - B2: 1200, B3: 400, B4: 300, B5: 150, B6: 200

4. **Enter actual amounts in column C:**
   - C2: 1250, C3: 380, C4: 275, C5: 175, C6: 200

### Step 4: Create Formulas for Analysis
5. **Calculate differences (D column):**
   - D2: =C2-B2 (Actual minus Budgeted)
   - Copy this formula to D3:D6 using fill handle

6. **Calculate percentage used (E column):**
   - E2: =IFERROR(C2/B2*100,"Error")
   - Copy this formula to E3:E6

### Step 5: Create Summary Totals
7. **Calculate totals in row 8:**
   - B8: =SUM(B2:B6) (Total budgeted)
   - C8: =SUM(C2:C6) (Total actual)
   - D8: =C8-B8 (Overall difference)
   - E8: =IFERROR(C8/B8*100,"Error") (Overall percentage)

### Step 6: Test Your Formulas
8. **Verify your calculations:**
   - B8 should equal 2250
   - C8 should equal 2280
   - D8 should equal 30 (over budget)
   - E8 should equal about 101.3%

9. **Test the dynamic nature:**
   - Change C3 (Food actual) to 450
   - Watch how D3, E3, C8, D8, and E8 all update automatically

### Step 7: Add Error Handling
10. **Test error handling:**
    - Temporarily change B2 to 0
    - Notice how E2 shows "Error" instead of #DIV/0!
    - Change B2 back to 1200

### Verification Checklist:
After completing this exercise, you should have demonstrated:
- ✅ **Formula Fundamentals**: All calculations start with =
- ✅ **Arithmetic Operators**: Used +, -, *, and / in formulas
- ✅ **Cell References**: Formulas reference other cells instead of hard-coded numbers
- ✅ **Formula Copying**: Used fill handle to copy formulas with automatic reference adjustment
- ✅ **Error Handling**: Used IFERROR to handle division by zero

### Expected Results:
Your budget calculator should:
- Show which categories are over/under budget
- Calculate percentages of budget used
- Update automatically when you change any input
- Handle errors gracefully with custom messages

---

## Key Differences Between Excel and Google Sheets

| Feature | Microsoft Excel | Google Sheets |
|---------|----------------|---------------|
| **Formula Autocomplete** | More comprehensive formula suggestions and tooltips | Basic formula suggestions |
| **Calculation Speed** | Faster for complex calculations | May be slower for complex formulas |
| **Array Formulas** | Uses LAMBDA and dynamic arrays | Uses ARRAYFORMULA function |
| **Formula Auditing** | Advanced formula auditing tools (trace precedents/dependents) | Basic error checking |
| **External References** | Can reference cells across workbooks | References across sheets within same spreadsheet only |
| **Formula Bar** | Resizable, with function argument hints | Fixed size, simpler interface |
| **Error Types** | More error types (#SPILL!, #CALC!) | Fewer error types |
| **F4 Key Function** | Toggles between relative and absolute references | Limited F4 functionality in browser |

---

## Additional Resources

### Official Documentation:
- **Excel**: [Overview of formulas in Excel](https://support.microsoft.com/en-us/office/overview-of-formulas-in-excel-ecfdc708-9162-49e8-b993-c311f47ca173)
- **Google Sheets**: [How to use formulas and functions](https://support.google.com/docs/answer/46977?hl=en&co=GENIE.Platform%3DDesktop)

### YouTube Video Tutorials:

**For Excel Basic Formulas:**
- [ExcelIsFun - Excel Formulas](https://www.youtube.com/c/ExcelIsFun) - Mike Girvin's comprehensive formula tutorials
- [Excel Campus - Formula Basics](https://www.youtube.com/c/ExcelCampus) - Jon Acampora's beginner-friendly formula instruction
- [Leila Gharani - Excel Formulas](https://www.youtube.com/c/LeilaGharani) - Professional formula techniques with downloadable practice files
- [TeachExcel - Basic Formulas](https://www.youtube.com/c/TeachExcel) - Step-by-step formula tutorials for beginners
- [MrExcel.com - Formula Tips](https://www.youtube.com/c/MrExcelcom) - Daily Excel formula tips and tricks

**For Google Sheets Formulas:**
- [Leila Gharani - Google Sheets Formulas](https://www.youtube.com/c/LeilaGharani) - Google Sheets formula tutorials and best practices
- [Google Workspace - Sheets Formulas](https://www.youtube.com/c/GoogleWorkspace) - Official Google tutorials for Sheets formulas
- [Teacher's Tech - Google Sheets](https://www.youtube.com/c/TeachersTech) - Beginner-friendly Google Sheets formula instruction

**Recommended Search Terms:**
- "Excel basic formulas tutorial for beginners"
- "Google Sheets formulas step by step"
- "Excel cell references and formula copying"
- "How to fix Excel formula errors"

---

## What's Next?

In Week 4, we'll build on your formula skills by learning:
- **Essential Functions**: SUM, AVERAGE, COUNT, MIN, MAX and more
- **Function Syntax**: How to structure function arguments properly
- **Text Functions**: Working with text data in formulas
- **Date Functions**: Calculations involving dates and times
- **Nested Functions**: Combining multiple functions for complex calculations

**Homework for this week**: 
1. Complete the Personal Budget Calculator exercise
2. Practice creating formulas with cell references instead of hard-coded numbers
3. Experiment with the fill handle to copy formulas across different ranges
4. Try to break your formulas intentionally to see different error messages, then fix them

The key to mastering formulas is understanding that they make your spreadsheets dynamic and powerful - when data changes, your calculations update automatically!
