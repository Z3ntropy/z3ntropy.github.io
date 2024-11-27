# Testing Prompt Engineering vs Fine-tuning for Anapestic Verse Generation

## Experiment Overview
This study compares two approaches to improving anapestic verse generation in large language models: prompt engineering and fine-tuning. The experiment uses three conditions: base model, prompt-engineered, and fine-tuned, all tested with identical evaluation criteria.

## Methodology

### Model Specifications
- Base Model: Claude-3 
- Fine-tuning Dataset: 1000 examples of anapestic verse from classical and contemporary sources
- Training Parameters: Learning rate 1e-5, 3 epochs, batch size 8

### Prompt Design Method
The lyrical prompt design consists of three components:
1. Structural Template: "Write a verse in anapestic meter (da-da-DUM, da-da-DUM)"
2. Example Demonstration: One clear example of anapestic meter
3. Constraint Specification: "Maintain strict anapestic meter throughout"

### Test Cases
Each condition will be tested with 100 different prompts, varying in:
- Requested topic
- Length (4-16 lines)
- Complexity of subject matter

### Control Measures
- Identical prompts across all three conditions
- Consistent sampling parameters (temperature = 0.7)
- Random prompt order presentation
- Blind evaluation of outputs

## Evaluation Metrics

### Primary Metrics
1. Meter Accuracy
   - Percentage of lines with correct anapestic meter
   - Deviation patterns from ideal meter
   - Consistency across line lengths

2. Semantic Coherence
   - Topic adherence
   - Logical flow between lines
   - Metaphor consistency

3. Creative Quality
   - Originality of expressions
   - Imagery effectiveness
   - Vocabulary richness

### Secondary Metrics
1. Generation Speed
2. Token efficiency
3. Error rate (incomplete or malformed outputs)

## Data Collection Process
1. Automated generation of outputs
2. Computational analysis of meter using natural language processing
3. Expert evaluation panel (3 poets, 2 linguists)
4. Statistical analysis of results

## Expected Results Analysis
1. Comparison of meter accuracy across conditions
2. Statistical significance testing
3. Qualitative analysis of creative differences
4. Error pattern analysis

## Mapping to Transformer Architecture

### Vector Space Considerations
- Analysis of how anapestic patterns are encoded in embedding space
- Attention pattern visualization for rhythmic structures
- Token-level analysis of stress patterns

### Attention Mechanism Impact
- Study of how attention heads process metrical patterns
- Analysis of positional encoding effects on meter
- Investigation of context window influence on rhythm maintenance

## Limitations and Considerations
1. Potential biases in training data
2. Limited scope of metrical variations
3. Subjective nature of creative evaluation
4. Processing resource constraints

## Future Extensions
1. Extension to other metrical forms
2. Cross-model comparisons
3. Hybrid approach testing
4. Long-form poetry generation

## Theoretical Implications
Discussion of how results inform our understanding of:
1. Language model rhythm processing
2. Trade-offs between fine-tuning and prompt engineering
3. Neural representations of poetic meter
4. Scalability of poetic form generation