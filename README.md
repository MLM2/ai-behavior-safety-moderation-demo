
# AI Behavior Safety Moderation Demo

**Interpretable, Transparent, and Steerable Safety Moderation for AI Behavior**  
Based on concepts from *SafetyAnalyst: Interpretable, Transparent, and Steerable Safety Moderation for AI Behavior* (arXiv, 2025).

## Purpose

This project demonstrates how the core ideas of the SafetyAnalyst framework can be adapted for use in **AI governance and AI policy contexts**, particularly in alignment with:

- NIST AI RMF
- ODNI Responsible AI Framework
- ACM ML Safety Taxonomy
- AMLAS safety assurance patterns

## Structure

- `notebooks/`
    - `harm_benefit_tree_generation.ipynb`: Demonstration of Chain-of-Thought generation of harm-benefit trees for AI behavior prompts.
    - `aggregation_model_demo.ipynb`: Simple white-box aggregation model with interpretable, steerable scoring of behavior harmfulness.
- `data/`: Sample prompts for testing.
- `scripts/`: Supporting code for aggregation model.
- `safety_moderation_argument_pattern.md`: Argument pattern inspired by AMLAS, adapted for this safety moderation framework.

## Starter Notebooks

This project includes starter notebooks to demonstrate key AI Behavior Safety Moderation techniques:

- `harm_benefit_tree_generation_NEW.ipynb`: Demonstrates Chain-of-Thought generation of harm-benefit trees for AI behavior prompts.
- `aggregation_model_demo.ipynb`: Demonstrates a transparent, steerable aggregation model to compute a total harmfulness score based on expert reasoning or LLM output.

These examples illustrate how concepts from the SafetyAnalyst framework can be adapted to support practical AI policy and governance needs, including alignment with NIST AI RMF and ODNI Responsible AI goals.

## Relevance to AI Policy and Governance

Transparent and steerable safety moderation of AI behavior is a critical emerging need for national security and intelligence applications. This demo illustrates how such techniques could be operationalized in AI governance workflows to support Responsible AI goals.

## References

- SafetyAnalyst: Interpretable, Transparent, and Steerable Safety Moderation for AI Behavior (arXiv, 2025)
- NIST AI RMF
- ODNI Responsible AI Framework
- ACM ML Safety Taxonomy
- AMLAS (Assurance of Machine Learning in Autonomous Systems)
