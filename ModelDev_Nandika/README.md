# Objectives

1. ## Understand and Implement Similarity Measures:
  - Load and prepare the data.
  - Convert the data into an m x m matrix using a similarity measure (e.g., Euclidean distance, Spearman rank correlation, or cosine similarity).

2. ## Develop Core Functions:
  - Create a function to map sets of symmetric matrices.
  - Develop a function to generate a doubly stochastic matrix.
  - Build a function to create a loss matrix based on the similarity measure matrix.

3. ## Solve Linear Systems:
  - Set up and solve the least squares problem.
  - Map the solution vector back to an m x m weighted adjacency matrix.

4. ## Construct a Dictionary and Visualization:
  - Create a dictionary with securities as keys and connection strengths as values.
  - Develop a visual representation of the underlying graph.

# Procedure

1. ## Data Loading and Preparation:
  - Load the financial time series data.
  - Clean and prepare the data, which may include interpolation and other preprocessing steps.

2. ## Matrix Conversion:
  - Convert the n x m data matrix into an m x m matrix using a selected similarity measure.

3. ## Function Development:
  - Mapping Function: Develop a function to map sets of symmetric matrices.
  - Doubly Stochastic Matrix Function: Create a function that generates a doubly stochastic matrix, utilizing the mapping function.
  - Loss Matrix Function: Build a function that takes the similarity measure matrix and returns a diagonal matrix of squared distances between element pairs based on known mappings.

4. ## Least Squares Problem:
  - Set up the least squares problem to solve the linear system.
  - Solve the linear system using least squares.
  - Map the solution vector back to an m x m weighted adjacency matrix.

5. ## Dictionary Construction and Visualization:
  - Construct a dictionary where the keys are the underlying securities, and the values are dictionaries with connection strengths, sorted in descending order.
  - Create a visual representation of the graph to illustrate the connections and strengths.

# Iterations

You will go through this process twice:

  1. ## First Iteration (Proof of Concept - POC):
  -  Focus on studying and understanding the underlying methods.
  - Use procedural code to implement the initial solution.
  - Select a single similarity method for the POC.
  - **Timeline**: Complete this iteration in 2 weeks.
  - **Presentation**: Prepare a presentation for both quantitative and non-quantitative audiences, detailing the meaning of outputs, the methods used, and the underlying mathematics.
  - Present your work and save all progress on your public GitHub account.

  2. ## Second Iteration (Software Development):
  - Refine the initial implementation.
  - Develop a robust module suitable for startup use.
  - Ensure the code is well-structured, documented, and user-friendly.
  - **Timeline** : Complete this iteration in 2 to 3 weeks.

# Deliverables

- First Iteration: Procedural code implementation, documentation of methods, and a presentation of your findings.
- Second Iteration: A well-documented software module, ready for use by non-developers, with clear instructions and user-friendly features.
