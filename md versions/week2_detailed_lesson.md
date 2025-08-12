# Week 2: Data Entry & Formatting - Detailed Lesson for Complete Beginners

## Learning Objectives:
By the end of this lesson, you will be able to:
- Understand different types of data in spreadsheets and how they behave
- Apply basic text formatting (fonts, bold, italic, colors) 
- Format numbers as currency, percentages, and dates
- Add borders and background colors to cells
- Adjust row heights and column widths effectively
- Use formatting to improve spreadsheet readability

---

## Topic 1: Data Types in Spreadsheets

### Understanding How Spreadsheets Interpret Data
Spreadsheets are smart - they automatically recognize different types of information and treat them differently. This is crucial to understand because it affects how your data looks and behaves in formulas.

### Visual Reference Screenshots:
- [Excel Data Types Example](https://www.datatrailmix.com/data-types-and-formatting-excel) - Shows how different data types appear and behave
- [Data Type Alignment](https://support.microsoft.com/en-us/office/convert-dates-stored-as-text-to-dates-8df7663e-98e6-4295-96e4-32a67ec0a680) - Demonstrates how Excel aligns different data types

### The Three Main Data Types:

#### 1. Text (Labels)
- **What it is**: Words, descriptions, names, addresses
- **How to recognize**: Automatically aligns to the left in cells
- **Examples**: "John Smith", "Product Description", "New York"
- **When to use**: Headers, names, descriptions, any non-numeric information

#### 2. Numbers
- **What it is**: Quantities, measurements, scores, prices (without symbols)
- **How to recognize**: Automatically aligns to the right in cells
- **Examples**: 25, 3.14, -150, 1000
- **When to use**: Quantities, calculations, measurements

#### 3. Dates and Times
- **What it is**: Calendar dates and time values
- **How to recognize**: Excel converts them to date format automatically
- **Examples**: 1/15/2024, Jan 15, 2024, 12:30 PM
- **When to use**: Scheduling, tracking, time-based calculations

### Step-by-Step: Understanding Data Types
1. **Open a new spreadsheet**
2. **In cell A1, type**: "Name" (this is text - notice it aligns left)
3. **In cell B1, type**: 100 (this is a number - notice it aligns right)
4. **In cell C1, type**: 1/15/2024 (Excel converts this to a date)
5. **In cell D1, type**: "100" (with quotes - this becomes text, aligns left)

### Common Data Type Issues and Solutions:

**Problem**: Numbers stored as text (can't be used in calculations)
- **How to identify**: Numbers that align to the left, or show a green triangle warning
- **Solution**: Use "Convert to Number" option or retype without quotes

**Problem**: Dates not recognized
- **Solution**: Use consistent date format like MM/DD/YYYY or DD/MM/YYYY

**Problem**: Leading zeros disappear (like 001, 002)
- **Solution**: Format cells as Text before entering data

### Practice Exercise: Data Type Recognition
1. **Create this data in column A**:
   - Row 1: Product Name
   - Row 2: iPhone 15
   - Row 3: 999
   - Row 4: 12/25/2024
   - Row 5: 025 (notice what happens)

2. **Observe the alignment** - text goes left, numbers go right
3. **Try entering 025 in a text-formatted cell** to see the difference

---

## Topic 2: Basic Text Formatting

### Making Your Text Look Professional
Text formatting makes your spreadsheets easier to read and more visually appealing. Just like in a word processor, you can change fonts, sizes, colors, and styles.

### Visual Reference Screenshots:
- [Excel Text Formatting Options](https://edu.gcfglobal.org/en/excel2016/formatting-cells/1/) - Shows the Font group with formatting buttons
- [Format Cells Dialog](https://support.microsoft.com/en-us/office/format-text-in-cells-ca112674-a567-4d6f-b5f8-3100aa27f40e) - Complete font formatting interface

### Font Basics

#### Changing Font Type:
**Step-by-Step Instructions:**
1. **Select the cell(s)** you want to format
2. **Go to Home tab** on the ribbon
3. **Click the dropdown arrow** next to the font name (usually "Calibri")
4. **Choose a new font** from the list
5. **Popular readable fonts**: Arial, Calibri, Times New Roman, Tahoma

**Quick Tip**: For business documents, stick to standard fonts like Arial or Calibri for readability.

#### Changing Font Size:
**Step-by-Step Instructions:**
1. **Select the cell(s)** you want to format
2. **Click the dropdown arrow** next to the font size (usually "11")
3. **Choose a larger or smaller size**
4. **Common sizes**: 
   - Headers: 14-18 points
   - Body text: 10-12 points
   - Titles: 16-24 points

### Text Styles and Effects

#### Making Text Bold, Italic, or Underlined:
**Method 1 - Using Buttons:**
1. **Select the text** you want to format
2. **Click the formatting button** in the Font group:
   - **B** for Bold
   - **I** for Italic  
   - **U** for Underline

**Method 2 - Using Keyboard Shortcuts:**
- **Bold**: Ctrl + B
- **Italic**: Ctrl + I
- **Underline**: Ctrl + U

#### Changing Font Color:
**Step-by-Step Instructions:**
1. **Select the cell(s)** you want to format
2. **Click the dropdown arrow** next to the Font Color button (looks like "A" with a colored underline)
3. **Choose a color** from the palette
4. **For custom colors**: Click "More Colors" at the bottom

**Best Practices**:
- Use dark colors for text (black, dark blue, dark gray)
- Ensure good contrast with the background
- Be consistent with color choices throughout your spreadsheet

### Cell Alignment and Text Wrapping

#### Text Alignment:
**Step-by-Step Instructions:**
1. **Select the cell(s)** you want to align
2. **In the Alignment group** on the Home tab, choose:
   - **Align Left**: Text starts at the left edge
   - **Center**: Text is centered in the cell
   - **Align Right**: Text starts at the right edge

#### Text Wrapping (for long text):
**When to use**: When text is too long for the cell width
**Step-by-Step Instructions:**
1. **Select the cell(s)** with long text
2. **Click "Wrap Text"** in the Alignment group
3. **The row height** will automatically adjust to show all text

### Practice Exercise: Text Formatting
1. **Create a header row** with these column titles:
   - Employee Name | Department | Salary | Start Date
2. **Format the headers**:
   - Make them **bold** (Ctrl + B)
   - Change font size to **14**
   - **Center-align** the text
   - Change color to **dark blue**
3. **Add sample data** below and practice different formatting options

---

## Topic 3: Number Formatting

### Making Numbers Meaningful
Raw numbers like "1000" or "0.15" don't tell the full story. Proper number formatting makes data immediately understandable and professional-looking.

### Visual Reference Screenshots:
- [Number Format Options](https://support.microsoft.com/en-us/office/available-number-formats-in-excel-0afe8f52-97db-41f1-b972-4b46e9f1e8d2) - Shows various number format categories
- [Currency Formatting](https://support.microsoft.com/en-us/office/format-numbers-as-currency-in-excel-0a03bb38-1a07-458d-9e30-2b54366bc7a4) - Demonstrates currency format application

### Currency Formatting

#### Basic Currency Formatting:
**Step-by-Step Instructions:**
1. **Select the cells** containing monetary values
2. **Click the "$" button** in the Number group (Accounting Number Format)
3. **Alternative method**: Click dropdown arrow next to Number Format and select "Currency"

**Keyboard Shortcut**: Ctrl + Shift + $ (applies default currency format)

#### Customizing Currency Format:
1. **Right-click** on selected cells
2. **Choose "Format Cells"** from the menu
3. **Select "Currency"** from the Category list
4. **Customize**:
   - **Symbol**: Choose $ € £ ¥ or others
   - **Decimal places**: Usually 2 for currency
   - **Negative numbers**: How to display negative values

### Percentage Formatting

#### Converting Numbers to Percentages:
**Important Note**: Excel treats percentages as decimals multiplied by 100
- 0.25 becomes 25%
- 1.5 becomes 150%

**Step-by-Step Instructions:**
1. **Enter your decimal values** (like 0.25 for 25%)
2. **Select the cells**
3. **Click the "%" button** in the Number group
4. **Or use keyboard shortcut**: Ctrl + Shift + %

#### Working with Existing Numbers:
If you have whole numbers that you want to display as percentages:
1. **Divide by 100 first** (25 becomes 0.25)
2. **Then apply percentage formatting**

### Date and Time Formatting

#### Common Date Formats:
Excel recognizes dates in many formats and can display them consistently:
- **Short Date**: 1/15/2024
- **Long Date**: Monday, January 15, 2024
- **Custom Date**: Jan-15-24

**Step-by-Step Instructions:**
1. **Enter dates** in any recognizable format
2. **Select the date cells**
3. **Right-click** and choose "Format Cells"
4. **Select "Date"** from Category list
5. **Choose your preferred format** from the Type list

#### Time Formatting:
- **12-hour format**: 2:30 PM
- **24-hour format**: 14:30
- **With seconds**: 2:30:45 PM

### Custom Number Formats

#### Creating Special Formats:
For unique display needs, you can create custom formats:

**Examples**:
- Phone numbers: (000) 000-0000
- Product codes: PRD-0000
- Adding text to numbers: 0" units"

**Step-by-Step Instructions:**
1. **Select cells** to format
2. **Right-click** → "Format Cells"
3. **Select "Custom"** from Category list
4. **Type your custom format** in the Type box
5. **Click OK**

### Practice Exercise: Number Formatting
1. **Create a sales report** with these columns:
   - Product | Price | Discount Rate | Sale Date
2. **Add sample data**:
   - Product: Laptop, Phone, Tablet
   - Price: 999.99, 699, 299.5
   - Discount: 0.1, 0.15, 0.05
   - Dates: Various dates
3. **Format appropriately**:
   - Price as **Currency** ($)
   - Discount Rate as **Percentage** (%)
   - Dates in **Short Date** format

---

## Topic 4: Cell Styling

### Making Data Stand Out
Cell styling includes borders, background colors, and visual effects that make your spreadsheets more readable and professional.

### Visual Reference Screenshots:
- [Cell Borders Interface](https://support.microsoft.com/en-us/office/apply-or-remove-cell-borders-on-a-worksheet-dc8a310b-92e3-46a7-9f17-2ab745810f4a) - Shows border options and application
- [Fill Color Options](https://support.microsoft.com/en-us/office/add-or-change-the-background-color-of-cells-in-excel-ac10f131-b847-428f-b656-d65375fb815e) - Demonstrates background color application

### Adding Cell Borders

#### Basic Border Application:
**Step-by-Step Instructions:**
1. **Select the cell(s)** you want to add borders to
2. **Click the dropdown arrow** next to the Borders button (looks like a grid)
3. **Choose a border style**:
   - **All Borders**: Adds borders around and inside selected cells
   - **Outline**: Adds border only around the outside
   - **Top Border, Bottom Border**: Adds specific edges
   - **No Border**: Removes existing borders

#### Custom Border Styling:
For more control over border appearance:
1. **Select your cells**
2. **Right-click** → "Format Cells"
3. **Click the "Border" tab**
4. **Choose**:
   - **Line Style**: Thin, thick, dashed, dotted
   - **Color**: Black, gray, or any color
   - **Border placement**: Click the preview area to add specific borders

**Common Border Uses**:
- **Table headers**: Thick bottom border
- **Data sections**: All borders for clarity
- **Totals row**: Thick top border
- **Important cells**: Thick outline border

### Background Colors and Fill

#### Adding Fill Colors:
**Step-by-Step Instructions:**
1. **Select the cell(s)** you want to color
2. **Click the dropdown arrow** next to the Fill Color button (paint bucket icon)
3. **Choose a color** from the palette
4. **For more colors**: Click "More Colors" at the bottom

#### Color Selection Best Practices:
- **Headers**: Light blue, light gray, or light green
- **Important data**: Light yellow for highlighting
- **Alternating rows**: Very light gray for easier reading
- **Avoid**: Bright colors that make text hard to read

#### Removing Fill Colors:
1. **Select the colored cells**
2. **Click Fill Color dropdown**
3. **Choose "No Fill"**

### Important Note About Gridlines:
When you add background colors, Excel's default gridlines disappear. To maintain visible cell divisions:
1. **Add borders** to colored cells
2. **Or use very light colors** that still show gridlines

### Format Painter Tool

#### Copying Formatting Quickly:
The Format Painter lets you copy all formatting from one cell to others:

**Step-by-Step Instructions:**
1. **Click on a cell** with the formatting you want to copy
2. **Click the Format Painter button** (paintbrush icon) in the Clipboard group
3. **Click on the cell(s)** you want to apply the formatting to
4. **For multiple applications**: Double-click Format Painter, then click multiple cells

### Practice Exercise: Cell Styling
1. **Create a monthly budget table**:
   - Headers: Category | Budgeted | Actual | Difference
2. **Style the table**:
   - **Header row**: Bold text, dark blue background, white font color
   - **Data rows**: Add all borders for clarity
   - **Total row**: Bold text, light gray background
   - **Negative differences**: Light red background
   - **Positive differences**: Light green background

---

## Topic 5: Row and Column Operations

### Controlling Layout and Appearance
Proper row and column sizing is essential for readable, professional-looking spreadsheets.

### Adjusting Column Widths

#### Auto-Sizing Columns:
**Method 1 - Double-click:**
1. **Position your cursor** on the right edge of the column header (between two column letters)
2. **Wait for the cursor** to change to a double-headed arrow
3. **Double-click** - Excel automatically sizes the column to fit the longest content

**Method 2 - Manual Dragging:**
1. **Position cursor** on the column edge
2. **Click and drag** to make wider or narrower
3. **Release** when desired width is reached

#### Setting Specific Column Widths:
1. **Right-click** on the column header (letter)
2. **Choose "Column Width"**
3. **Enter a specific number** (measured in characters)
4. **Click OK**

### Adjusting Row Heights

#### Auto-Sizing Rows:
**Similar to columns:**
1. **Position cursor** on the bottom edge of a row number
2. **Double-click** to auto-size for content
3. **Or drag** to manually adjust height

#### Setting Specific Row Heights:
1. **Right-click** on the row number
2. **Choose "Row Height"**
3. **Enter a specific number** (measured in points)
4. **Click OK**

### Hiding and Unhiding Rows/Columns

#### Hiding Columns or Rows:
**When to use**: To temporarily remove columns/rows from view without deleting data

**Step-by-Step Instructions:**
1. **Select the column(s) or row(s)** by clicking the header
2. **Right-click** on the selected header
3. **Choose "Hide"**

#### Unhiding Columns or Rows:
1. **Select the columns/rows** on either side of the hidden ones
2. **Right-click** on the selection
3. **Choose "Unhide"**

### Freezing Panes

#### Keeping Headers Visible:
**When to use**: When you have large datasets and want to keep headers visible while scrolling

**Step-by-Step Instructions:**
1. **Click on the cell** below and to the right of what you want to freeze
   - To freeze row 1: Click on cell A2
   - To freeze column A: Click on cell B1
   - To freeze both: Click on cell B2
2. **Go to View tab** on the ribbon
3. **Click "Freeze Panes"**
4. **Choose "Freeze Panes"** from the dropdown

#### Unfreezing Panes:
1. **Go to View tab**
2. **Click "Freeze Panes"**
3. **Choose "Unfreeze Panes"**

### Practice Exercise: Row and Column Operations
1. **Create a product inventory list** with many columns and rows
2. **Practice these operations**:
   - Auto-size all columns to fit content
   - Make the "Description" column extra wide
   - Hide the "Internal Code" column
   - Increase row height for better readability
   - Freeze the header row and first column
   - Scroll around to see the freeze effect

---

## Comprehensive Practice Exercise: Employee Information Dashboard

Now let's put all Week 2 skills together in one meaningful project that covers all the formatting concepts we've learned.

### Project Overview:
Create a professional employee information dashboard that demonstrates data types, text formatting, number formatting, and cell styling.

### Step 1: Set Up Your Data Structure
1. **Create these column headers** in row 1:
   - A1: Employee ID
   - B1: Full Name  
   - C1: Department
   - D1: Hire Date
   - E1: Annual Salary
   - F1: Performance Score
   - G1: Bonus Rate
   - H1: Email Address

### Step 2: Enter Sample Data
Add these sample employees (rows 2-6):
- **Row 2**: 001 | John Smith | Sales | 1/15/2020 | 75000 | 4.2 | 0.05 | john.smith@company.com
- **Row 3**: 002 | Sarah Johnson | Marketing | 3/22/2019 | 68000 | 4.8 | 0.08 | sarah.johnson@company.com  
- **Row 4**: 003 | Mike Wilson | IT | 7/10/2021 | 85000 | 4.0 | 0.03 | mike.wilson@company.com
- **Row 5**: 004 | Lisa Brown | HR | 11/5/2018 | 72000 | 4.6 | 0.06 | lisa.brown@company.com
- **Row 6**: 005 | David Lee | Finance | 2/28/2022 | 78000 | 4.4 | 0.04 | david.lee@company.com

### Step 3: Format the Headers
1. **Select the header row** (A1:H1)
2. **Apply these formats**:
   - **Font**: Change to Arial, size 12
   - **Style**: Bold (Ctrl + B)
   - **Alignment**: Center align
   - **Background**: Dark blue fill color
   - **Font color**: White
   - **Borders**: All borders with thick line style

### Step 4: Format Data Types Appropriately
1. **Employee ID column (A)**:
   - Format as Text to preserve leading zeros
2. **Hire Date column (D)**:
   - Format as Short Date (MM/DD/YYYY)
3. **Annual Salary column (E)**:
   - Format as Currency ($)
4. **Bonus Rate column (G)**:
   - Format as Percentage (%)

### Step 5: Apply Cell Styling
1. **Data rows** (A2:H6):
   - Add all borders (thin lines)
   - Alternate row colors: Light gray for rows 2, 4, 6
2. **Department column** (C):
   - Use different background colors for each department:
     - Sales: Light blue
     - Marketing: Light green  
     - IT: Light orange
     - HR: Light yellow
     - Finance: Light purple

### Step 6: Optimize Layout
1. **Auto-size all columns** to fit content properly
2. **Make the Email column wider** if needed
3. **Increase row height** slightly for better readability
4. **Freeze the header row** so it stays visible when scrolling

### Step 7: Add a Summary Section
1. **In cell A8**: Type "Summary Statistics"
2. **Format A8**: Bold, larger font, centered across columns A-C
3. **Create summary labels** in column A:
   - A9: Total Employees
   - A10: Average Salary  
   - A11: Average Performance
4. **Add the actual values** in column B (for now, just type them manually):
   - B9: 5
   - B10: $75,600
   - B11: 4.4
5. **Format the summary section** with borders and light background color

### Verification Checklist:
After completing this exercise, you should have demonstrated:
- ✅ **Data Types**: Text (names), numbers (scores), currency (salary), percentages (bonus), dates
- ✅ **Text Formatting**: Different fonts, bold headers, centered text, font colors
- ✅ **Number Formatting**: Currency symbols, percentage signs, proper date display
- ✅ **Cell Styling**: Background colors, borders, visual hierarchy
- ✅ **Layout Control**: Proper column widths, row heights, frozen headers

### Expected Result:
Your dashboard should look professional and be easy to read, with:
- Clear, formatted headers that stand out
- Properly formatted data that's immediately understandable
- Good use of colors and borders for organization
- Appropriate sizing for all content

---

## Key Differences Between Excel and Google Sheets

| Feature | Microsoft Excel | Google Sheets |
|---------|----------------|---------------|
| **Formatting Options** | More extensive formatting options including advanced borders, patterns, and effects | Fewer but sufficient formatting choices for most needs |
| **Conditional Formatting** | More rules and options available | Basic conditional formatting supported |
| **Custom Number Formats** | Extensive custom number format options with complex codes | Limited custom number format options |
| **Cell Styles** | Built-in cell styles gallery with predefined combinations | No pre-defined styles gallery, must create manually |
| **Theme Support** | Comprehensive theme capabilities affecting entire workbook | Limited theme options |
| **Format Painter** | Can double-click to apply multiple times | Single use only, must click for each application |
| **Currency Symbols** | Supports wide range of international currency symbols | Basic currency symbol support |
| **Date Formats** | More date format options and regional settings | Fewer date format variations |

---

## Additional Resources

### Official Documentation:
- **Excel**: [Format numbers in cells](https://support.microsoft.com/en-us/office/format-numbers-in-cells-7fc5bf93-7913-40ff-bd4a-60ce90755a6d)
- **Google Sheets**: [Format your spreadsheet](https://support.google.com/docs/answer/46973?hl=en&co=GENIE.Platform%3DDesktop)

### YouTube Video Tutorials:

**For Excel Data Entry & Formatting:**
- [ExcelIsFun - Excel Basics Series](https://www.youtube.com/c/ExcelIsFun) - Over 3,000 videos covering formatting, data entry, and number formatting
- [Leila Gharani - Excel Tutorials](https://www.youtube.com/c/LeilaGharani) - Professional formatting techniques with downloadable practice files
- [Excel Campus - Formatting Tutorials](https://www.youtube.com/c/ExcelCampus) - Jon Acampora's comprehensive formatting and styling guides
- [Microsoft Excel Official Channel](https://www.youtube.com/c/MicrosoftExcel) - Official Microsoft tutorials on Excel formatting features
- [TeachExcel - Excel Tutorials](https://www.youtube.com/c/TeachExcel) - Step-by-step formatting and data entry tutorials

**For Google Sheets Formatting:**
- [Leila Gharani - Google Sheets Tutorials](https://www.youtube.com/c/LeilaGharani) - Practical Google Sheets formatting tips and tutorials
- [Teacher's Tech - Google Sheets](https://www.youtube.com/c/TeachersTech) - Beginner-friendly Google Sheets formatting instruction
- [Google Workspace - Official Tutorials](https://www.youtube.com/c/GoogleWorkspace) - Official Google tutorials for Sheets formatting features
- [Ben Collins - Google Sheets](https://www.youtube.com/c/benlcollins) - Advanced Google Sheets techniques and formatting

**Recommended Specific Video Topics:**
Search these channels for videos covering:
- "Excel cell formatting and borders"
- "Number formatting currency and percentages" 
- "Excel data entry best practices"
- "Google Sheets formatting tutorial for beginners"

---

## What's Next?

In Week 3, we'll build on your formatting skills by learning:
- **Basic Formulas**: Creating calculations using arithmetic operators
- **Cell References**: How to reference other cells in formulas
- **Formula Copying**: Making formulas work across multiple cells
- **Error Handling**: Understanding and fixing common formula errors

**Homework for this week**: 
1. Complete the Employee Information Dashboard exercise
2. Practice formatting a personal expense tracker or any data you work with regularly
3. Experiment with different color combinations and formatting styles to develop your design sense

The key to mastering formatting is practice - the more you work with these tools, the more natural they'll become!
