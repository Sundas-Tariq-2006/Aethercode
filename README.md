AetherCode ML-Guided Automated Program Repair with Formal Verification

AetherCode is a research-grade automated program repair system for Python that goes beyond "tests pass"
It mathematically verifies that a fix is correct.

Most AI coding tools suggest fixes. AetherCode proves them.

How it works:
1. Bug detected in your Python code
2. LLM generates multiple candidate fixes
3. ML policy ranks fixes by predicted correctness (with uncertainty estimation)
4. Z3-based formal verifier confirms the top fix mathematically
5. You get a verified, safe repair — not just a guess

Why AetherCode?
Smart budget allocation ML prioritizes best fixes first, no blind brute-force
Cross-project generalization trained to work on unseen codebases
Honest reporting clearly distinguishes verified, test-passing, and inconclusive results
Research-backed built toward Q1 publication standards

Tech Stack:
Python · Z3 · CodeBERT · scikit-learn · FastAPI · Docker · pytest · GitHub Actions · MLflow

Status: Active Research & Development
Target: Automated repair of Python type errors and null dereference bugs
