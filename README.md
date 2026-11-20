# Weekly Model Comparison Airflow DAG

An Apache Airflow pipeline built with Astro (Astro Runtime 12.1.1) using the TaskFlow API to preprocess breast cancer data, train a Logistic Regression baseline and a Random Forest candidate in parallel, and evaluate both models weekly.

## DAG Details
* **DAG ID:** `weekly_model_comparison`
* **Schedule:** `@weekly` (Start Date: `2026-01-01`, `catchup=False`)

## Start Command
Run the local Airflow environment using the Astro CLI:

```bash
astro dev start# Weekly Model Comparison Airflow DAG

An Apache Airflow pipeline built with Astro (Astro Runtime 12.1.1) using the TaskFlow API to preprocess breast cancer data, train a Logistic Regression baseline and a Random Forest candidate in parallel, and evaluate both models weekly.

## DAG Details
* **DAG ID:** `weekly_model_comparison`
* **Schedule:** `@weekly` (Start Date: `2026-01-01`, `catchup=False`)

## Start Command
Run the local Airflow environment using the Astro CLI:

```bash
astro dev start
