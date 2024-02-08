# Countdown Calendar Generator

## Overview
The Countdown Calendar Generator is a Python function that calculates and displays the number of days left until a specified end date. It provides a simple yet effective way to visualize countdowns for future events or deadlines.

## Usage
1. Set the desired end date in the code.
2. Run the Python script.
3. The countdown calendar will be printed, showing each day leading up to the end date along with the corresponding number of days left.

## Example
```python
from datetime import datetime

# Set the end date
end_date = datetime(2024, 12, 31).date()

# Run the countdown calendar function
countdown_calendar(end_date)
