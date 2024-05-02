# Harry-Potter-Sorting-Hat

## Project Overview:

The objective of this project is to create a machine learning model that mimics the sorting hat ceremony from the Harry Potter series. The goal is to assign individuals to Hogwarts houses based on their traits and characteristics, similar to the system used on this [website](https://www.wizardingworld.com/news/discover-your-hogwarts-house-on-wizarding-world).

### Description of the Sorting Hat Ceremony:

In the Harry Potter series, the sorting hat assigns individuals to one of four houses at Hogwarts (Gryffindor, Slytherin, Hufflepuff, Ravenclaw) based on their unique qualities.

You can watch this [video](https://youtu.be/T1G4wzRO_tc) to learn more about the ceremony and the distinctive traits of each house.

## The Process:

1. **Data Collection:**

   Data was collected from Harry Potter fan sites and the official Wizarding World website. This data was structured into a format suitable for analysis.

2. **Cleaning the Data:**

   Natural language processing (NLP) techniques were applied to clean the data, removing unnecessary words and punctuation to prepare it for analysis.

3. **Selecting Important Words:**

   After cleaning, important keywords describing each Hogwarts house were identified (e.g., Gryffindor with bravery, Slytherin with ambition).

4. **Turning Words into Numbers:**

   These keywords were transformed into numerical representations using techniques like word embedding.

5. **Building the Model:**

   A logistic regression model was used to compare the characteristics of each Hogwarts house with the answers provided by individuals to determine their likely house affiliation.

6. **Answering Questions:**

   A quiz was created with questions related to the traits of each house. Based on a person's answers, the model calculates their probable house.

   [Quiz Link](https://docs.google.com/forms/d/1Ljg0RrwUhLxY27ycOlPGEyig0Smye3YUFbI8YRG7Ok4/edit)

7. **Results:**

   The model analyzes the quiz responses and assigns a percentage match to each house, indicating the most suitable Hogwarts house for the individual.

## Limitations and Future Considerations:

**Limitations:**
- The information collected was strongly skewed towards Gryffindor, as most main characters in the series belong to that house. This resulted in limited data for other houses, making it challenging to build an accurate system without synthetic data.
- Although we explored different models such as random forest and decision trees, the results were subpar, likely due to the limited data available for houses other than Gryffindor.

**Future Considerations:**
- Collecting more diverse data sources to balance the representation of traits across all Hogwarts houses.
- Experimenting with advanced natural language processing techniques and neural network architectures to improve the accuracy and robustness of the sorting model.
- Enhancing the user interface of the sorting quiz and integrating additional interactive features for a richer user experience.

This project utilizes machine learning techniques to recreate the enchanting experience of the sorting hat ceremony from Harry Potter in an interactive digital format.
