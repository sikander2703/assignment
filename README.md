# assignment
#"Base Frequency in Random Numbers"

## Code Exploration

### Initialization

The journey begins with the initialization of a mapping dictionary that associates digits 0-9 with themselves and extends to include letters A-Z. This mapping serves as the foundation for creating diverse random numbers.

### Generating Random Numbers

The code proceeds to generate a substantial sample size of 5 million random numbers. Each number is constructed by choosing digits from the mapping dictionary, with the possibility of expanding the base through a coin toss.

### Reverse Mapping

To analyze the generated numbers, a reverse mapping dictionary is created. This dictionary facilitates the conversion of the highest digit in a number back to its corresponding base.

### Frequency Analysis

The code then explores the frequency distribution of the highest bases in the generated random numbers. The results are stored in a dictionary, with bases as keys and their respective frequencies normalized to the sample size.

## Visualizing the Data

The documentary culminates in a visual representation of the base frequencies. A bar chart is crafted using the Matplotlib library, showcasing the distribution and highlighting the prevalence of certain bases in the generated random numbers.

## Conclusion

In this exploration of base frequencies in random numbers, we've witnessed the intricate interplay between randomness, digit mapping, and base representation. The code serves as a gateway to understanding the underlying patterns that emerge when randomness is harnessed within a defined structure.

Thank you for joining us on this journey through the captivating realm of random numbers and their bases.
