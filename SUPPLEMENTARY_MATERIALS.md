# DART-SQL Supplementary Materials

This repository contains the prompt templates and selected experimental settings accompanying the paper *DART-SQL: Dynamic Action Routing for Text-to-SQL*.

## Contents

- `prompts/`: the eight prompt templates used by the DART-SQL action modules and action selector.
- `settings/selected_settings.yaml`: the routing, retrieval, candidate-budget, and tuning settings that can be verified from the archived experiment materials.

The repository intentionally contains no executable source code, benchmark data, model weights, API credentials, or experimental outputs. BIRD and Spider should be obtained from their official distributions.

The action prompts were adapted from the Alpha-SQL prompt design and extended with the current reasoning state and valid-action set required by dynamic action routing. See `LICENSE` for the license notice associated with the adapted materials.

