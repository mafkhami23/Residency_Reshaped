# Kano_Analysis


This project is based on the principles of Kano Model, which is often used in product development and customer satisfaction analysis.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use **Kano.py**, make sure you have Python 3.x installed. You can install the necessary dependencies using the following command:

```bash
pip install -r requirements.txt
```

Alternatively, you can install the dependencies manually if they are not listed in a requirements file.

## Usage

After cloning the repository and installing the dependencies, you can run **Kano.py** using the command line or import it as a module into your own Python projects.

### Running from Command Line:

```bash
python Kano.py [options]
```

### Importing into Your Python Script:

```python
from Kano import Kano

# Example usage
kano = Kano()
kano.some_function()
```

## Features
- **[Data Cleaning]**:
- The script includes data cleaning steps, such as setting column headers, removing unwanted rows, and preparing the dataset for further analysis.

 - **[Data Duplication for Backup]**:
 - The code creates a duplicate of the original dataset (dq=df) for safe manipulation without altering the original data.

- **[Kano Model Analysis:]**
- The script implements the Kano model, which is used to classify customer preferences into categories (e.g., must-haves, performance attributes, and delighters) to understand and prioritize product features based on their impact on satisfaction.

- **[Kano Data Processing]**:
- The script likely includes logic to process survey data and classify responses into the Kano categories, possibly using responses related to expectations versus satisfaction.

- **[Kano Graphic Generation]**:
- Using libraries like matplotlib or seaborn, the script generates Kano graphics, which visually represent the relationship between product features and customer satisfaction.
  
## Example

Below is a basic example of how to use **Kano.py**:

```python
# Example code snippet demonstrating functionality
kano_model = Kano()
kano_model.calculate([input_parameters])
```

## Contributing

Contributions are welcome! If you'd like to contribute to **Kano.py**, please fork the repository and submit a pull request with your improvements.

1. Fork the repository
2. Create a new branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
