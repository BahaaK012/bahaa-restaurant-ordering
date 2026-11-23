# bahaa-restaurant-ordering

Advanced OOP Final Project - Topic 1: Restaurant Ordering.

A library of Java classes (no main method, no UI) that manages the orders of a small
restaurant. All behavior is executed through JUnit 5 tests.

## Domain
- Entities: MenuItem (Food, Drink, Dessert), Order, Customer, Payment
- Operations: get menu, create order, add/remove item, get total, pay, cancel
- Rules: at least two payment methods with different rules

## Planned architecture
- Strategy pattern: payment methods (cash, credit card)
- Factory pattern: creation of menu items
- Custom unchecked exception hierarchy (base: `RestaurantException`)
- Order state guard: OPEN, PAID, CANCELLED

## Packages
`com.restaurant.exception`, `model`, `payment`, `service`

## Run tests
`mvn test`
