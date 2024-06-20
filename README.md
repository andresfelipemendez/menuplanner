# Calendar Menu Meal Planner

This repository contains a Go and HTMX-based application that allows you to plan your weekly or monthly grocery shopping lists according to the meals you have planned.

## Features

- **Calendar View**: Plan your meals on a weekly or monthly basis using an intuitive calendar interface.
- **Grocery List Generation**: Automatically generate grocery shopping lists based on your meal plans.
- **Responsive Design**: Access and manage your meal plans and shopping lists from any device.

## Technologies Used

- **Go**: Backend logic and API.
- **HTMX**: Frontend interactivity and dynamic content loading.

## Getting Started

### Prerequisites

- [Go](https://golang.org/doc/install) installed on your local machine.
- [HTMX](https://htmx.org/) included in your project.

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/andresfelipemendez/menuplanner.git
    cd menuplanner
    ```

2. Install dependencies:
    ```sh
    go mod download
    ```

3. Run the application:
    ```sh
    go run main.go
    ```

4. Open your browser and navigate to `http://localhost:8080` to view the application.

## Usage

1. **Plan Meals**: Use the calendar interface to add your meals for each day.
2. **Generate Shopping Lists**: Once your meals are planned, generate your shopping list for the week or month.
3. **Shop**: Use the generated list to shop for your groceries efficiently.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
