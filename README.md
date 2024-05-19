# Optimizing Traveling Salesman Problem Solutions Through FunSearch Technology

## Project Overview

This project tackles the classic combinatorial optimization challenge known as the Traveling Salesman Problem (TSP) using the innovative FunSearch framework. Our goal is to find the shortest possible route that allows a salesman to visit a set of cities and return to the starting city, visiting each city only once. The solution leverages the power of pretrained language models, evolutionary algorithms, and distributed computing to iteratively improve TSP solutions.

## Why Choose the TSP Problem

- **Theoretical Significance and Practical Value:** TSP is a fundamental problem in computer science and operations research with numerous practical applications in logistics, transportation, and supply chain management.
- **Challenge:** TSP is an NP-hard problem, which makes it a perfect candidate for studying advanced algorithms and mathematical theories.
- **Career Development:** Solving complex algorithmic problems like TSP enhances skills crucial for technical roles, such as data scientists and algorithm engineers.

## Methodology

### FunSearch Framework Overview

The FunSearch framework consists of five main components:

1. **Specification:** Defines the initial problem and solution evaluation criteria.
2. **Pretrained LLM:** Generates improvements to the solution based on given prompts.
3. **Evaluation:** Tests and scores the generated solutions.
4. **Prompt:** Guides the LLM in creating better solutions.
5. **Program Database:** Stores and evolves the best solutions over time.

### Detailed Execution Process

1. **Specification:** 
   - Defines how to assess and evolve potential solutions.
   - Heuristic algorithm guides the search for efficient routes based on a priority function.

2. **Pretrained LLM:**
   - Generates new code iterations to improve the priority function.
   - Utilizes HTTP requests to communicate with external APIs, ensuring continuous code refinement.

3. **Evaluation:**
   - Solutions are tested in a Sandbox environment to ensure safety and efficiency.
   - Evaluator assesses the effectiveness and efficiency of the solutions based on predefined metrics.

4. **Program Database and Prompt:**
   - Stores multiple versions of solutions, organized into "islands" to ensure diversity.
   - Prompts guide the LLM in generating new solutions based on the best-performing programs.

## Results

### Dataset Visualization

We visualized the locations of the nodes (cities) in the TSP instances to gain an intuitive understanding of the problem space and verify data integrity. 

### Final Results

After running 100 training cycles, we significantly improved the TSP solution. The total travel distance was reduced from -838152 to -2915, demonstrating the effectiveness of the FunSearch framework in optimizing routes.

### Insights

The iterative and evolutionary approach of FunSearch proves highly effective in refining strategies over time. This project highlights the value of integrating pretrained language models with evolutionary algorithms, offering promising implications for various complex scheduling and routing problems.

## Conclusion

The FunSearch project demonstrates the robustness of iterative learning systems in solving the Traveling Salesman Problem. This framework can be adapted to other complex optimization problems, making it a powerful tool in fields such as logistics, networking, and urban planning.

## References

1. Y. Bang, S. Cahyawijaya, N. Lee, et al. A multitask, multilingual, multimodal evaluation of chatgpt on reasoning, hallucination, and interactivity. arXiv preprint arXiv:2302.04023, 2023.
2. A. Borji. A categorical archive of chatgpt failures. arXiv preprint arXiv:2302.03494, 2022.
3. X. Chen, M. Lin, N. Schärli, et al. Teaching large language models to self-debug. arXiv preprint arXiv:2304.05128, 2023.
4. B. Romera-Paredes, M. Barekatain, A. Novikov, et al. Mathematical discoveries from program search with large language models. Nature, 625:468–475, 2024.

## How to Run

1. Clone the repository: `git clone https://github.com/your_username/your_repository.git`
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the main script: `python main.py`

For more details, refer to the [project report](./final_report.pdf).
