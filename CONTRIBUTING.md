# Contributing to Your iOS Journey

This is a personal learning repository, but these guidelines will help you maintain consistency as you document your learning journey.

## When to Document a Concept

Document a concept when:
- You find something confusing or non-intuitive
- You struggle with a particular iOS/Swift feature
- You discover an "aha!" moment worth preserving
- You want to explain something to your future self
- You encounter a pattern you want to remember

## Documentation Workflow

### 1. Encounter a Confusing Concept
When you're coding and hit something confusing, make a note of it.

### 2. Research and Learn
- Read documentation
- Watch tutorials
- Write test code
- Ask questions

### 3. Document Your Understanding
- Use the concept template from `/templates/concept-template.md`
- Write in your own words
- Be honest about what confused you
- Include practical examples

### 4. Create a Mini-Project (Optional)
If the concept warrants it, create a small project to practice.

### 5. Link Related Concepts
Create connections between related topics in your documentation.

## Branching Strategy

Use Git branches to organize your learning:

- `main` - Stable, well-understood concepts
- `feature/[concept-name]` - While learning/documenting a new concept
- `experiment/[idea]` - For trying out new ideas

Example workflow:
```bash
# Start learning a new concept
git checkout -b feature/understanding-combine

# Document as you learn
git add concepts/concurrency/combine-basics.md
git commit -m "Add notes on Combine publishers"

# Create a mini-project
git add mini-projects/combine-demo/
git commit -m "Add Combine demo project"

# Merge when you feel confident
git checkout main
git merge feature/understanding-combine
```

## Commit Message Guidelines

Write clear commit messages that describe your learning:

- `Add notes on [concept]` - New concept documentation
- `Update [concept] with [insight]` - Refining understanding
- `Add mini-project for [concept]` - New practice project
- `Fix errors in [concept] explanation` - Corrections

## File Naming Conventions

- Use lowercase with hyphens: `optional-binding.md`
- Be descriptive: `understanding-async-await.md` not `async.md`
- Group related concepts: `closures-basics.md`, `closures-advanced.md`

## Keeping the Repository Organized

### Regular Maintenance

- Update the concept index in `concepts/README.md`
- Remove outdated or incorrect information
- Refactor documentation as understanding improves
- Archive old mini-projects if they're no longer relevant

### Quality Over Quantity

- It's better to have a few well-documented concepts than many shallow ones
- Revisit and refine existing documentation
- Add to concepts as you learn more about them

## Using Issues (Optional)

You can use GitHub Issues to:
- Track concepts you want to learn next
- Note questions you have about a topic
- Plan mini-projects
- Set learning goals

Example labels:
- `concept: swift`
- `concept: uikit`
- `concept: swiftui`
- `status: learning`
- `status: need-practice`
- `priority: high`

## Remember

This repository is **your** learning journey. There's no right or wrong way to document. What matters is that it helps **you** learn and retain information. Be consistent, be honest, and keep building!
