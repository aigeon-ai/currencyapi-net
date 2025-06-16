markdown
# CurrencyAPI.net MCP Server

Welcome to the CurrencyAPI.net MCP server! This powerful service provides real-time currency conversion and historical data for over 152 currencies, including both fiat and cryptocurrencies. Whether you need live exchange rates or historical currency data, CurrencyAPI.net has you covered.

## Features

- **Live Exchange Rates**: Updated every 60 seconds for the MEGA plan, every 10 minutes for the ULTRA plan, and hourly for the PRO and FREE plans.
- **Comprehensive Currency Support**: Includes 152 world currencies and popular cryptocurrencies like Bitcoin, Litecoin, Ethereum, and more.
- **Historical Data**: Access historical currency rates dating back to the year 2000.
- **Easy Conversion**: Convert currencies instantly with the convert tool.
- **User-Friendly Documentation**: Comprehensive and easy-to-follow documentation to help you get started quickly.

## Authentication

Upon creating an account, you will receive a unique 36-character API key. This key acts as a secure password; keep it safe and do not share it with others.

## Tools and Endpoints

CurrencyAPI.net offers a variety of tools to meet your currency conversion needs:

### Convert Tool
- **Description**: Convert a specified amount from one currency to another.
- **Parameters**: Amount, From Currency Code, To Currency Code, Output Format (JSON or XML).

### Rates Tool
- **Description**: Retrieve live currency conversion rates for a specified currency.
- **Parameters**: Base Currency, Output Format (JSON or XML).

### History Tool
- **Description**: Access historical currency rates for a specific day.
- **Parameters**: Date, Base Currency, Output Format (JSON or XML).

### Timeframe Tool
- **Description**: View historical currency rates within a specified timeframe.
- **Parameters**: Start Date, End Date, Base Currency, Output Format (JSON or XML).

### Currencies Tool
- **Description**: List all supported currencies along with their currency codes.
- **Parameters**: Output Format (JSON or XML).

## Error Codes

In case of any issues, the server provides clear error codes with descriptions to help you troubleshoot:

- `400`: Missing API key.
- `401`: Invalid API key.
- `402`: Non-existent function requested.
- `403`: Non-existent currency pair requested.
- `405`: Monthly subscription allowance exceeded.
- `406`: Invalid base currency.
- `407`: HTTPS encryption not allowed on current plan.
- `408`: Base currency selection not allowed on current plan.
- `410`: 'From' parameter not set.
- `411`: 'To' parameter not set.
- `412`: 'Amount' parameter not set.
- `413`: Invalid amount value.
- `414`: Unsupported or invalid currency.
- `415`: Unsupported currency in limit parameter.
- `416`: Endpoint access not allowed on current plan.
- `417`: No historical data for the specified date.
- `418`: Incorrect date format.
- `419`: Timeframe exceeds 365 days.
- `500`: Technical fault on the server.

By leveraging these tools and features, CurrencyAPI.net MCP server provides a robust solution for all your currency conversion and historical data needs.