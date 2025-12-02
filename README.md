# Render Prop Pattern React

This project shows key React patterns in a simple demo. It uses Faker to generate product and company data and displays them with interactive lists. The List component demonstrates the render prop pattern by letting you decide how each item is rendered while keeping the list generic. Companies reveal extra details on hover, and products show name, price, and description, highlighting conditional rendering with useState.

A higher-order component called withToggles adds open and collapse functionality to existing components, showing how HOCs extend behavior without changing the original code. The Counter component uses React Context to share state and actions, with subcomponents like Count, Label, Increase, and Decrease attached as properties, illustrating the compound component pattern.

Together these examples highlight render props for flexible rendering, HOCs for reusability, and context with compound components for shared state, making the project a compact showcase of practical React design patterns.
