# 🧮 EMI Calculator with GST

A comprehensive EMI (Equated Monthly Installment) calculator that includes GST (Goods and Services Tax) calculation for loans. This tool helps users calculate their monthly loan payments along with applicable tax components.

## 📋 Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [EMI Calculation Formula](#emi-calculation-formula)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## ✨ Features

- 💰 **Accurate EMI Calculation** - Calculate monthly installments with precision
- 📊 **GST Integration** - Include GST in your loan calculations
- 📈 **Detailed Breakdown** - View principal amount, interest, and GST components
- 🔄 **Real-time Updates** - Instant calculation as you input values
- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- 📉 **Amortization Schedule** - View payment breakdown over the loan tenure
- 💡 **Interactive UI** - User-friendly interface with intuitive controls

## 🎯 Demo

[Live Demo Link](https://roxtar007.github.io/emi-calculator/)

## 📦 Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Git installed on your system
- Basic text editor or IDE (VS Code, Sublime Text, etc.)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/roXtar007/emi-calculator.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd emi-calculator
   ```

3. **Open the project**
   - Simply open `index.html` in your web browser
   - Or use a local server (recommended):
   
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

4. **Access the application**
   - Open your browser and navigate to `http://localhost:8000`

## 🚀 Usage

### Basic Usage

1. **Enter Loan Amount** - Input the principal loan amount
2. **Set Interest Rate** - Enter the annual interest rate (in percentage)
3. **Choose Tenure** - Select the loan tenure (in months)
4. **Processing Fee** - Input applicable processing fee
5. **First Installment date** - Input first installment due date or select from calender option
### Input Parameters

| Parameter | Description | Example |
|-----------|-------------|---------|
| Principal | The loan amount you want to borrow | ₹500,000 |
| Annual Rate | Annual interest rate | 10.5% |
| Months | Duration of the loan | 24 months |
| Processing Fee | Applicable processing fee | 299 |
| First Installment | First EMI due date | 15/08/1947 |

### Output Details

The calculator provides:
- **Monthly EMI** - Your monthly installment amount
- **Total Interest** - Total interest payable over the loan period
- **GST Amount** - GST applicable on the interest
- **Total Amount Payable** - Principal + Interest + GST
- **Amortization Table** - Month-wise payment breakdown

## 📐 EMI Calculation Formula

### Standard EMI Formula

```
EMI = [P × R × (1+R)^N] / [(1+R)^N-1]
```

Where:
- **P** = Principal loan amount
- **R** = Monthly interest rate (Annual Rate / 12 / 100)
- **N** = Loan tenure in months

### With GST Calculation

```
Total Interest = (EMI × N) - P
GST Amount = Total Interest × (GST Rate / 100)
Total Amount = P + Total Interest + GST Amount
```


## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

### How to Contribute

1. **Fork the Project**
2. **Create your Feature Branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your Changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the Branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Contribution Guidelines

- Write clear, commented code
- Follow existing code style and conventions
- Test your changes thoroughly
- Update documentation as needed
- Add screenshots for UI changes

## 🐛 Bug Reports

If you find a bug, please open an issue with:
- Clear title and description
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)
- Browser and OS information

## 💡 Feature Requests

We welcome feature requests! Please open an issue with:
- Clear description of the feature
- Use case/benefit
- Any relevant examples or mockups

## 📝 License

Distributed under the MIT License. See `LICENSE` file for more information.

## 👤 Author

**roXtar007**

- GitHub: [@roXtar007](https://github.com/roXtar007)
- Repository: [emi-calculator](https://github.com/roXtar007/emi-calculator)

## 🙏 Acknowledgments

- Inspiration from various financial calculators
- AI for coding

## 📞 Contact

For any queries or suggestions, please:
- Open an issue on GitHub
- Star ⭐ the repository if you find it helpful!

---

<div align="center">

### ⭐ Don't forget to star this repository if you found it helpful!

Made with AI by roXtar007 

</div>

---


## ❓ FAQ

**Q: What is EMI?**  
A: EMI (Equated Monthly Installment) is a fixed payment amount made by a borrower to a lender at a specified date each month.

**Q: How is GST calculated on loans?**  
A: GST is typically applied on the interest component of the loan, not on the principal amount.

**Q: Can I use this for different types of loans?**  
A: Yes! This calculator works for home loans, car loans, personal loans, and any other type of installment-based loans.

**Q: Is the calculation accurate?**  
A: Yes, the calculator uses standard financial formulas used by banks and financial institutions.

---

**Last Updated:** May 2026
