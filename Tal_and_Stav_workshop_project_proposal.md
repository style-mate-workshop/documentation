**1\. What is the problem you are trying to solve?**

Many people struggle with putting together stylish and appropriate daily outfits for various occasions. This challenge often leads to frustration, wasted time, and missed opportunities to make a good impression or feel confident.  
For example, after spending time trying to find the right outfit, you might rush out of the house only to realize you’re dressed in a T-shirt and jeans while it’s raining—a situation that could have been avoided with better outfit planning.

This issue highlights the need for a solution that combines convenience, style, and practicality to help people dress appropriately and confidently for their day, without the stress of decision-making.

**2\. Describe briefly, in high level your presumed solution**

We are developing an intuitive app that helps users quickly choose the perfect outfit based on the weather, occasion, and personal style preferences.  
The app will:

- Provide outfit recommendations based on the user's wardrobe and local weather conditions.
- Allow users to specify the occasion (e.g., work, casual outing, formal event).
- Save time by eliminating the guessing of outfit planning, ensuring users leave the house looking stylish and feeling confident.

**3\. Are there other approaches?**

- Choosing the outfit the day before:Users can plan their outfits the night before, taking time to consider the weather, occasion, and personal preferences. This proactive method can reduce morning stress but still requires effort and decision-making, which some may find inconvenient.
- **Hiring a stylist to create built-in outfits and sets:  
    **A professional stylist can help users by creating pre-designed outfit combinations tailored to their wardrobe and preferences. While effective, this approach can be costly and time-consuming, making it less accessible for everyday use.

While these methods address the problem, they often involve either significant manual effort or higher costs. Our app combines the benefits of automation, personalization, and simplicity to provide a seamless and efficient solution.

**4\. Who are the expected users of the application?**

All people of all genders. The app will be able to create styling based on your gender preferences (feminine, masculine, and unisex).

The app is designed for anyone seeking assistance in creating stylish and occasion-appropriate outfits. It approaches to people of all genders and includes the flexibility to generate outfit recommendations based on the user's styling preferences:

- Feminine.
- Masculine.
- Unisex (for users who prefer gender-neutral styling options).

This inclusivity ensures that the app appeals to a large audience, from busy professionals to students, or anyone who values convenience and style.

**5\. What will be the main features and flows of the (different) user(s)?**

- In order to use the app, the user will be required to take pictures of all items in its closet. The app will be able to label the item according to its type (shirts, pants, jackets…). The user will be able to manage its closet (delete, update, and add).
- You will be prompted to complete a short questionnaire and it will generate an outfit recommendation according to your closet. You will be able to approve or deny it. If the suggested outfit is denied, it will keep generating outfits until you will find a one you like.
- The user will create an outfit from the current items list, and the app will give it a score and a feedback (suggestions for improvement).

**6\. Are there any external dependencies?**

- System for auto-labeling images.
- We are planning to write in Python and Java.
- Using microservices with Kubernetes and Docker.
- We will need at least one database using NOSQL.
- We implement an event-driven architecture.
- Using AI API for generating the outfits and scoring them.