---
sidebar_label: 'System Analysis Approaches'
sidebar_position: 2
---

# System Analysis Approaches

## Traditional Approaches

### Structured Analysis (SA)
- **Definition**: Systematic approach breaking systems into manageable components
- **Key Elements**:
  - Decomposition (breaking systems into parts)
  - Modeling techniques (DFDs, ERDs)
  - Top-down approach
  - Data flow analysis

### Waterfall Model
- **The OG sequential approach** - perfect when requirements are set in stone
- **Phases**:
  1. Requirements → 2. Design → 3. Implementation → 4. Verification → 5. Maintenance
- **When to use**: Small projects with clear requirements (like building a calculator)
- **Pros**: Simple, clear milestones, easy to manage
- **Cons**: Inflexible - changing requirements will wreck your timeline

## Modern Approaches

### Object-Oriented Analysis (OOA)
- **Think in objects** - just like Java/Python does
- **UML diagrams** are your best friends here
- **VS Structured Analysis**:
  - SA: "Here's data and here's how we process it"
  - OOA: "Here's objects that contain data AND behavior"

### Agile Analysis
- **For when requirements change faster than your coffee gets cold**
- Key features:
  - Sprints (2-4 week development cycles)
  - Daily standups
  - Continuous feedback
- **Pros**: Adaptable, customer-focused, faster delivery
- **Cons**: Needs disciplined teams, documentation can suffer

### Rapid Application Development (RAD)
- **"Build fast, fail fast, fix fast"** mentality
- **Phases**:
  1. Business modeling → 2. Data modeling → 3. Process modeling → 4. App generation → 5. Testing
- **Perfect for**: Prototypes and MVPs

## Battle Royale: Traditional vs Modern
| Factor        | Traditional              | Modern                   |
|---------------|--------------------------|--------------------------|
| Flexibility   | Rigid                   | Adaptable                |
| Documentation | Heavy                   | Minimal                  |
| Speed         | Slow                    | Fast                     |
| Best for      | Stable requirements     | Dynamic environments     |
