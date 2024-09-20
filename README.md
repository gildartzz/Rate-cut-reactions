# Fed Rate Cuts Impact on Gold and S&P 500

This project visualizes the impact of Federal Reserve rate cuts on Gold prices and the S&P 500 index. It creates two separate visualizations showing the market reactions 1 month and 2 months after significant rate cuts from 2001 to 2020.

## Overview

The script analyzes how Gold and the S&P 500 responded to major Fed rate cuts over the past two decades. It generates two bar charts:
1. Market reaction 1 month after each rate cut
2. Market reaction 2 months after each rate cut

These visualizations provide insights into short-term and medium-term market responses to monetary policy changes.

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- yfinance
- Fred


## Data Source

- Gold prices and S&P 500 index data are fetched from Yahoo Finance using the `yfinance` library.
- Rate cut dates and magnitudes are hardcoded in the script based on historical Fed actions.

## Visualization Details

- The x-axis shows the dates of significant Fed rate cuts.
- The y-axis represents the percentage change in asset prices.
- Gold is represented by gold-colored bars, and S&P 500 by blue bars.
- The magnitude of each rate cut is displayed below the corresponding date.

## Contributing

Contributions to improve the script or extend the analysis are welcome. Please feel free to submit a pull request or open an issue for discussion.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For any questions or feedback, please open an issue in this repository.
