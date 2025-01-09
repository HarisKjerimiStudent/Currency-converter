
# Realtime Currency Converter


This project demonstrates how to build a simple currency converter using three different technologies:
- **Python**: A command-line tool for currency conversion.
- **JavaScript**: A static HTML + JS frontend for in-browser conversion.
- **C#**: An ASP.NET Razor Page for a dynamic web-based converter.

The main problem this porject solves is convert one currency to another easily without problems or complications.

## How to Run

### Python Version
1. Run `currency_converter.py` using Python 3.x.
2. Follow the on-screen prompts to perform currency conversions.

### Static HTML + JavaScript Version
1. Open `index.html` in any modern web browser.
2. Enter the amount and select currencies to perform the conversion.

### C# ASP.NET Version
1. Add `currency_converter_aspnet.cshtml` to an ASP.NET Core Razor Pages project in Visual Studio.
2. Run the project to access the web-based converter.

## Highlight
The higlight of this project the many currencies offered which is provided in this code:
 <script>
        const exchangeRates = {
            "USD": { "EUR": 0.85, "GBP": 0.75, "BAM": 1.74, "ALL": 103.5, "HRK": 6.65, "MKD": 54.3, "RSD": 108.6, "CNY": 6.47, "JPY": 110.1 },
            "EUR": { "USD": 1.18, "GBP": 0.88, "BAM": 1.96, "ALL": 122.5, "HRK": 7.53, "MKD": 61.5, "RSD": 117.3, "CNY": 7.6, "JPY": 129.5 },
            "GBP": { "USD": 1.33, "EUR": 1.14, "BAM": 2.32, "ALL": 137.8, "HRK": 8.51, "MKD": 69.5, "RSD": 132.8, "CNY": 8.9, "JPY": 148.2 },
            "BAM": { "USD": 0.57, "EUR": 0.51, "GBP": 0.43, "ALL": 59.4, "HRK": 3.78, "MKD": 31.3, "RSD": 59.9, "CNY": 3.9, "JPY": 67.5 },
            "ALL": { "USD": 0.0096, "EUR": 0.0082, "GBP": 0.0073, "BAM": 0.017, "HRK": 0.064, "MKD": 0.53, "RSD": 1.0, "CNY": 0.065, "JPY": 1.14 },
            "HRK": { "USD": 0.15, "EUR": 0.13, "GBP": 0.12, "BAM": 0.27, "ALL": 15.7, "MKD": 8.0, "RSD": 15.8, "CNY": 1.02, "JPY": 17.9 },
            "MKD": { "USD": 0.018, "EUR": 0.016, "GBP": 0.014, "BAM": 0.032, "ALL": 1.89, "HRK": 0.13, "RSD": 2.0, "CNY": 0.13, "JPY": 2.23 },
            "RSD": { "USD": 0.0092, "EUR": 0.0085, "GBP": 0.0075, "BAM": 0.017, "ALL": 1.0, "HRK": 0.063, "MKD": 0.50, "CNY": 0.063, "JPY": 1.12 },
            "CNY": { "USD": 0.15, "EUR": 0.13, "GBP": 0.11, "BAM": 0.26, "ALL": 15.4, "HRK": 1.0, "MKD": 7.7, "RSD": 15.9, "JPY": 17.2 },
            "JPY": { "USD": 0.0091, "EUR": 0.0077, "GBP": 0.0067, "BAM": 0.014, "ALL": 0.88, "HRK": 0.056, "MKD": 0.45, "RSD": 0.89, "CNY": 0.058 }
        };

  
The components 

![The input bar](./image.png)

![The curreny selectors](./currency.jpg)

![The convert button](./button.jpg)

Contact

Maintainer - Haris Kjerimi - 210302156@student.ius.edu.ba

## License
This project is licensed under the MIT License.
