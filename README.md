# ABM Assignment 1 - Smart Food Delivery Agents

## Folders
- report/ - the report as PDF, and the same content as an editable Word file
- food_delivery_agents/ - the Python code
  - agent1_simple_reflex.py ... agent7_contextual.py - the seven agents
  - base.py, environment.py - shared agent base and the simulated world
  - run_tests.py, benchmark.py - the three test cases and the 1,000-delivery benchmark
  - diagram_lib.py, diagrams_1_4.py, diagrams_5_7.py - draw the architecture diagrams
  - diagrams/ - the seven architecture diagrams (PNG)
  - results/ - saved output of the tests and the benchmark
- dashboard/ - interactive dashboard, one HTML file (open it in any browser)

## Run
Python 3.13, standard library only (matplotlib is needed only to redraw the diagrams).

    cd food_delivery_agents
    python run_tests.py          # the three test cases (add --why for each agent's reasoning)
    python benchmark.py          # the 1,000-delivery benchmark
    python diagrams_5_7.py       # redraw the seven diagrams

Every random choice is seeded, so the results are identical on every run.
