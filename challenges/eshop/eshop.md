# DEVELOP A SHOPPING CART

**Topics to be used:**

- **Topic 1: Plan:** Use Plan Mode to create a better strategy before coding. Review and finalize a high-level plan, and start implementation only after approval. 
- **Topic 2: Code:** Transition to Agent Mode. Once the plan is approved, implement the code according to the approved plan.
- **Topic 3: Test:** Test the application to ensure all features work as expected.
- **Topic 4: Generate Chat Instructions:** Create a rulebook of custom Copilot instructions to ensure consistency, enforce best practices and coding standards, and minimize AI hallucinations in future challenges.
- **Topic 5: Prompt Files:** Create targeted, reusable prompts for specific activities like code generation or conducting code reviews.
- **Topic 6: Custom Agents:** Documentation Specialist Agent – Responsible for creating and updating README files or other project documentation, ensuring consistent structure and formatting.

## Objective

The goal of this challenge is to develop a shopping cart. The shopping cart should allow users to add and remove products. The products will be automobile parts. The application should have a REST API to manage the products and the shopping cart.

## INSTRUCTIONS

### 1. Choose a programming language of your choice.

### 2. Topic selected is automobile parts. You can use the automobileParts.json file in the root of the eshop project to get the list of automobile parts for building the Rest API.

### 3. Develop the shop cart. You can use the following steps as a guide:

- Create a Rest API with methods to:
    - Get the automobile parts list with page offset and limit.
    - Get automobile part details by id.
    - Search automobile parts by name, description, manufacturer, price.
- Create a list of products in the main page.
- Create a search bar to filter the products.
- Navigate to the description page when the user clicks on a product.
- (Optional) Slicer to filter the products by price.
- Create a shop cart.
    - Add a product to the shop cart.
    - Remove a product from the shop cart.
    - Calculate the total price of the products in the shop cart.
