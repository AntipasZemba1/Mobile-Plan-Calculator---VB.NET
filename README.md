#📱 Mobile Plan Calculator - VB.NET

Overview
This is a basic Windows Forms application built using Visual Basic .NET. The program allows users to calculate their monthly mobile phone plan cost based on selected options such as talk minutes, phone type, text messaging, and video chat features. It then applies tax and displays the final monthly cost.

🧩 Features
Selectable talk time plans:

800 Minutes – $19.99

1500 Minutes – $28.99

Unlimited Talk – $39.99

Choose a phone type:

Samsung – $29.99

iPhone – $39.99

Customer's Own Phone – $0

Optional add-ons:

Unlimited Text Messaging – $10.00

Video Chat – $15.00

Calculates:

Subtotal

Tax (7.5%)

Total Monthly Cost

Buttons to calculate, clear, and exit the form.

🛠 How It Works
User Input:

The user selects one radio button from each group:

Talk Plan (800, 1500, Unlimited)

Phone Type (Samsung, iPhone, Own Phone)

Optionally checks one or both add-on checkboxes:

Unlimited Text

Video Chat

Calculation Logic:

Adds base plan rate

Adds phone cost (if not using own phone)

Adds selected add-on(s)

Applies a 7.5% tax

Displays subtotal, tax amount, and total

Reset and Exit:

"Clear" resets all selections and labels

"Exit" closes the application

🧾 UI Elements
Radio Buttons:

rad800min, rad1500min, radUnlimitedTalk

radSamsung, radIphone, radCustmerPhone

Checkboxes:

chckUnlimitedText, chckVideoChat

Labels (Outputs):

lblSubtotal, lblTax, lblMonthlyTotal

Buttons:

btnCalculate – Calculates cost

btnClear – Clears inputs

btnExit – Closes the application

