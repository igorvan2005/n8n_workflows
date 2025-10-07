# Copywriting Master Subagent Implementation Guide

## Overview
This guide shows how to implement and use the Copywriting Master subagent that incorporates the combined wisdom of history's greatest copywriters from course.md.

## Installation Steps

### 1. Create the Subagent
Use Claude Code's `/agents` command to create the subagent:

```
/agents
```

Then follow these steps:
1. Choose "Project" scope (so it's available for this project)
2. Name: `copywriting-master`
3. Description: `Master copywriter that applies legendary techniques`
4. Copy the system prompt from `copywriting-master-subagent.json`
5. Select these tools:
   - Read, Write, Edit, MultiEdit
   - Grep, Glob
   - WebFetch, WebSearch
   - Context7 MCP tools (if available)

### 2. Verify Installation
Test the subagent with:
```
Use the copywriting-master subagent to analyze this headline: "Get Rich Quick"
```

## Key Features

### 1. Research-First Approach (Hopkins/Bencivenga)
The subagent always starts with comprehensive research:
- Product analysis
- Market study
- Competitor research
- Customer interviews

### 2. Audience Awareness Matching (Schwartz)
Automatically determines audience awareness level:
- Unaware → Problem education
- Problem Aware → Solution introduction
- Solution Aware → Product differentiation
- Product Aware → Conviction building
- Most Aware → Offer optimization

### 3. Scientific Testing Framework (Hopkins/Caples)
Every output includes testing recommendations:
- What elements to test
- How to measure results
- Statistical significance guidelines

### 4. Psychological Trigger Mapping (Halbert/Sugarman)
Systematically applies 11 core triggers:
- Greed, Fear, Guilt, Anger
- Exclusivity, Urgency, Authority
- Social Proof, Reciprocity, Consistency, Liking

## Usage Examples

### Example 1: Sales Letter Creation
```
Use the copywriting-master subagent to write a sales letter for a productivity app targeting busy entrepreneurs.
```

The subagent will:
1. Ask research questions about the app
2. Determine entrepreneur awareness level
3. Create USP based on unique features
4. Map psychological triggers (time scarcity, success desire)
5. Write using Collier Letter Formula
6. Provide testing recommendations

### Example 2: Headline Optimization
```
Use the copywriting-master subagent to improve this headline: "Our Software Helps You Work Better"
```

Expected output:
- 10 alternative headlines using Caples formulas
- Explanation of psychological triggers used
- A/B testing suggestions
- Audience awareness considerations

### Example 3: Email Campaign Strategy
```
Use the copywriting-master subagent to create a 7-email nurture sequence for SaaS trial users.
```

The subagent will:
1. Map the customer journey
2. Assign specific legendary techniques to each email
3. Create psychological progression
4. Include specific subject lines and CTAs
5. Provide engagement metrics to track

## Advanced Integrations

### 1. With Context7 MCP
The subagent can research current marketing trends:
```
Use the copywriting-master subagent to research latest copywriting techniques from modern marketing libraries.
```

### 2. With GitHub Research
For code-related products:
```
Use the copywriting-master subagent to create developer-focused copy after researching the codebase.
```

### 3. Web Research Integration
For market research:
```
Use the copywriting-master subagent to analyze competitor copy and create differentiated messaging.
```

## Best Practices

### 1. Always Provide Context
Give the subagent:
- Product details
- Target audience
- Business goals
- Current challenges
- Competitive landscape

### 2. Request Specific Outputs
Be clear about what you want:
- "Create a landing page"
- "Optimize email subject lines"
- "Write ad copy for Facebook"
- "Design A/B tests"

### 3. Use Iterative Refinement
Build on the subagent's work:
```
Use the copywriting-master subagent to refine this copy based on Bernbach's creative principles.
```

## Measurement Framework

The subagent includes built-in measurement recommendations:

### Primary Metrics
- Conversion rates
- Click-through rates
- Open rates (email)
- Cost per acquisition

### Secondary Metrics
- Time on page
- Scroll depth
- Social shares
- Brand recall

### Testing Protocol
- Single variable changes
- Statistical significance requirements
- Test duration guidelines
- Result interpretation

## Troubleshooting

### If Subagent Responses Are Too Generic
- Provide more specific product details
- Include target audience research
- Specify the awareness level
- Give competitive context

### If Output Lacks Psychological Depth
- Request specific trigger analysis
- Ask for emotional journey mapping
- Specify the desired emotional outcome

### If Testing Recommendations Are Unclear
- Ask for step-by-step testing protocols
- Request specific metrics to track
- Get sample size calculations

## Example Project Workflow

### 1. Product Launch Campaign
```
1. Use copywriting-master for market research
2. Create positioning statement
3. Develop key messages
4. Write launch sequence
5. Design A/B tests
6. Create measurement dashboard
```

### 2. Conversion Optimization
```
1. Analyze current copy performance
2. Identify psychological gaps
3. Apply legendary techniques
4. Create test variations
5. Implement tracking
6. Analyze results
```

## Legendary Technique Quick Reference

| Technique | When to Use | Example Application |
|-----------|-------------|-------------------|
| Hopkins Testing | Always | A/B test headlines |
| Schwartz Awareness | Audience research | Match message sophistication |
| Halbert Triggers | Emotional appeal | Use fear for security products |
| Caples Headlines | Attention grabbing | "They Laughed When..." format |
| Ogilvy Research | Foundation work | Deep product analysis |
| Bernbach Creativity | Breakthrough needed | Unexpected honest approach |
| Reeves USP | Positioning | "Melts in mouth, not hand" |
| Collier Formula | Long-form copy | 7-step sales letter |
| Kennedy Character | Brand building | Develop strong personality |
| Bencivenga Research | Competitive advantage | 80/20 research/writing rule |

This subagent transforms copywriting from guesswork into a scientific, legendary-technique-powered process that delivers measurable results.