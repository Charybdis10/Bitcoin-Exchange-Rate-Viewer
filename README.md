# Bitcoin Exchange Rate Viewer

This HTML webpage allows users to view live Bitcoin exchange rates in different currencies (USD, EUR, GBP). Users can select their preferred currency and click the "Submit" button to fetch and display the current Bitcoin exchange rate.

## Usage

To use the Bitcoin Exchange Rate Viewer, open the HTML file in a web browser. Select your preferred currency (USD, EUR, GBP), click the "Submit" button, and the current Bitcoin exchange rate for the selected currency will be displayed below the form.

```bash
# Example: Open the HTML file in a web browser
firefox bitcoin_exchange_rate_viewer.html
```

## Webpage Styling

The webpage is styled with a light blue background and enlarged text for better visibility. The style is defined using CSS in the `<style>` section of the HTML.

## JavaScript Functionality

The conversion logic is implemented using JavaScript. The `convert()` function is triggered when the form is submitted. It checks which currency radio button is selected and fetches the latest Bitcoin exchange rates from "https://api.coindesk.com/v1/bpi/currentprice.json". The corresponding exchange rate is then displayed below the form.

## HTML Elements

- **Radio Buttons (`USD`, `EUR`, `GBP`)**: Users can select their preferred currency.
- **Submit Button**: Clicking the "Submit" button triggers the conversion process.
- **Exchange Rate Result (`ans`)**: The current Bitcoin exchange rate in the selected currency is displayed below the form.

## Notes

- The exchange rates are fetched from the CoinDesk API, so an internet connection is required.
- The webpage is designed for simplicity and ease of use.
- Feel free to modify the code to suit your needs or integrate additional features.

If you encounter any issues or have suggestions for improvement, please let us know.
