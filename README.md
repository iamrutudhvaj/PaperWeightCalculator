# Paper Weight Calculator

A simple, user-friendly web application for calculating paper weight and cost based on paper dimensions, GSM (grams per square meter), quantity, and price rate.

![Paper Weight Calculator](https://raw.githubusercontent.com/iamrutudhvaj/PaperWeightCalculator/main/screenshot.png)

## Features

- Calculate paper weight in kilograms based on:
  - Length and width (supports multiple units: mm, cm, inch, meter)
  - GSM (grams per square meter)
  - Quantity
- Calculate total cost based on weight and price per kilogram
- Clean, responsive UI that works well on both desktop and mobile devices
- Simple and intuitive interface with real-time results

## How It Works

The calculator uses the following formula to determine paper weight:

```
Paper Weight (kg) = (Length in meters × Width in meters × GSM × Quantity) ÷ 1000
```

Where:
- Length and width are converted to meters from the selected unit
- GSM is the paper's weight in grams per square meter
- Quantity is the number of sheets
- The division by 1000 converts from grams to kilograms

## Usage

1. Enter the paper dimensions (length and width)
2. Select the appropriate unit of measurement for each dimension
3. Enter the GSM (grams per square meter) of the paper
4. Set the quantity of sheets
5. Enter the cost per kilogram
6. Click "Calculate" to see the results
7. Use "Clear" to reset all fields

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Responsive design for both desktop and mobile devices

## Installation

No installation is required. Simply open the `index.html` file in any modern web browser to use the calculator.

```bash
# Optional: If you want to run it with a local server
# Using Python
python -m http.server 8000

# Or with Node.js
npx http-server
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Author

Rutudhvaj Bodar

---

*Note: This tool is designed to provide estimates for paper weight and cost calculations. While we aim for accuracy, results may vary slightly from actual weights.*
