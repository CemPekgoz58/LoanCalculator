# Loan Calculator

A simple Java Swing application to calculate loan repayments using the annuity method, including taxes such as KKDF and BSMV.

## Features

- Input fields for:
  - Loan amount
  - Monthly interest rate (percentage)
  - Term length in months
- Calculates equal monthly installments (annuity)
- Displays detailed breakdown per installment:
  - Monthly payment
  - Principal amount
  - Interest amount
  - KKDF tax
  - BSMV tax
  - Remaining loan balance
- Totals for all payments and taxes
- User-friendly GUI interface

## How to Run

1. Clone or download the repository.
2. Open the project in an IDE supporting Java Swing (e.g., NetBeans, IntelliJ IDEA, Eclipse).
3. Build and run the `KrediHesaplama` class.
4. Enter the loan details and click the "Calculate" button.

## Technical Details

- Java Swing is used for the GUI.
- The calculation assumes KKDF and BSMV taxes at 15% each on the interest.
- Monthly interest rate should be provided as a percentage (e.g., 3.39 for 3.39%).
- The annuity formula is applied to calculate fixed monthly payments including taxes.

## License

This project is open source and free to use.

---

If you want me to help you prepare a `README.md` file ready to push, I can create it as a text file for you as well.
