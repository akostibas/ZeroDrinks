# Drink Tracking Shortcuts for Apple Health

A simple, privacy-focused solution for tracking alcohol consumption using Apple Shortcuts and Apple Health.

## About

This repository hosts a single-page website that provides two Apple Shortcuts designed to help you track and monitor your alcohol consumption:

- **Log Drink**: Quick one-tap logging of alcohol consumption
- **Zero Drinks**: Advanced tracking with sliding window averages and insights

## Website

Visit: [https://akostibas.github.io/ZeroDrinks/](https://akostibas.github.io/ZeroDrinks/)

## The Shortcuts

### Log Drink

A simple shortcut that adds one "Alcohol Consumed" health sample to Apple Health. Perfect for adding to your home screen, lock screen, or watch complication for quick logging each time you have a drink.

### Zero Drinks

A more comprehensive shortcut that:
- Adds "0 drinks" data points when no drinks were consumed (Apple Health ignores null data days, which throws off averages)
- Calculates a configurable X-day sliding window average
- Provides positive reinforcement messages when you had zero drinks the previous day
- Asks reflective questions ("How do you feel?") when you did have drinks

## Privacy

All data is stored locally in Apple Health on your device. No data is transmitted to external servers or stored elsewhere. Your health information remains completely private and under your control.

## Development

The website is a single HTML file with inline CSS and JavaScript for simplicity and portability. No build process or dependencies required.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## License

MIT License - Feel free to use and modify as needed.

## Acknowledgments

Built with a focus on privacy, simplicity, and seamless integration with Apple Health.
