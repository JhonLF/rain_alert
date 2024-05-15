# Rain Alert ☔️

This Python script checks if rain is expected in your area today and sends an SMS notification using Twilio if rain is predicted. It uses the OpenWeatherMap API to retrieve weather data and the Twilio API to send SMS messages.

## Configuration

1. Get your API keys:
    - OpenWeatherMap API: [Sign up here](https://home.openweathermap.org/users/sign_up).
    - Twilio API: [Sign up here](https://www.twilio.com/try-twilio).

2. Replace the placeholder values in the script:
    - `__YOUR_OWM_API_KEY__` with your OpenWeatherMap API key.
    - `__YOUR_TWILIO_ACCOUNT_ID__` with your Twilio Account SID.
    - `__YOUR_TWILIO_AUTH_TOKEN__` with your Twilio Auth Token.
    - Replace `"YOUR TWILIO VIRTUAL NUMBER"` with your Twilio virtual phone number.
    - Replace `"YOUR TWILIO VERIFIED REAL NUMBER"` with your verified real phone number.

## Usage

1. Run the script:

    ```bash
    python main.py
    ```

2. If rain is expected, you will receive an SMS notification reminding you to bring an umbrella.

## Notes

- Make sure to have a Twilio account with SMS capabilities and a verified phone number.
- Check your Twilio usage and pricing for SMS messages.
- You can customize the message body and add more functionality as needed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
