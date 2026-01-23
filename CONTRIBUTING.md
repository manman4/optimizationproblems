# Contributing Guidelines

Thank you for your interest in contributing to the Optimization Problems repository! This document provides guidelines for contributing new problems, updating bounds, and maintaining the repository.

## How to Contribute

### Adding a New Problem

1. **Fork the repository** and create a new branch for your contribution
2. **Create a new file** in the `problems/` directory using the naming convention: `problem-name.md` (use lowercase and hyphens)
3. **Use the template**: Copy the structure from [template.md](template.md)
4. **Fill in all sections**:
   - Provide a clear problem statement with mathematical notation
   - Include the current best known bounds with proper citations
   - Add relevant historical context
   - List complete references with journal/book information
5. **Update README.md**: Add a link to your problem in the appropriate category
6. **Submit a pull request** with a clear description of the problem and its significance

### Updating Existing Bounds

1. **Fork the repository** and create a new branch
2. **Edit the relevant problem file**:
   - Update the bounds section with new values
   - Add complete citations for the new result
   - Update the history section with the new development
   - Update the "Last Updated" field
3. **Provide evidence**: In your pull request description, include:
   - Link to the paper or preprint
   - Brief explanation of the technique used
   - How this improves on previous bounds
4. **Submit a pull request**

### Improving Documentation

We welcome improvements to:
- Problem statements (clarification, better notation)
- Additional references and context
- Corrections to existing information
- Better organization and categorization

## Quality Standards

### Mathematical Rigor

- **Precision**: Use precise mathematical notation and definitions
- **Accuracy**: Ensure all bounds and results are correctly stated
- **Citations**: Provide complete, verifiable references
- **Clarity**: Write for a graduate-level mathematical audience

### Citation Format

Use standard academic citation format:

```
Author(s) (Year). "Title". Journal/Book, Volume(Issue), Pages.
```

For preprints:
```
Author(s) (Year). "Title". arXiv:XXXX.XXXXX [category].
```

### Problem Categories

Current categories include:
- **Analysis and Inequalities**: Sobolev, Hardy, isoperimetric inequalities, etc.
- **Discrete Mathematics**: Combinatorial optimization, extremal problems
- **Number Theory**: Optimization problems in number theory
- **Geometry**: Geometric optimization problems

When adding a new category:
1. Ensure there are at least 2-3 problems in the category
2. Add it to the README with a brief description

## Review Process

### What We Look For

- **Correctness**: Mathematical accuracy of the problem and bounds
- **Relevance**: Problems should involve optimization of a specific constant
- **Significance**: Problems should be of research interest
- **Documentation**: Clear, well-documented with proper references
- **Formatting**: Follows the template and style guidelines

### Timeline

- Initial review: Within 1 week
- Feedback and revisions: As needed
- Merge: Once approved by maintainers

## Style Guidelines

### Markdown Formatting

- Use headers (#, ##, ###) consistently
- Use code blocks for mathematical expressions: \`expression\`
- Use bullet points for lists
- Keep lines reasonably short (80-100 characters when possible)

### Mathematical Notation

- Use standard LaTeX-style notation in markdown
- Define all variables and symbols
- Use consistent notation within and across problems
- For display math, consider using LaTeX syntax (will render on GitHub)

### File Naming

- Use lowercase letters
- Use hyphens to separate words
- Be descriptive but concise
- Examples: `sobolev-inequality.md`, `hardy-inequality.md`

## Code of Conduct

### Be Respectful

- Assume good faith
- Be constructive in feedback
- Respect different mathematical perspectives and approaches
- Focus on the mathematics, not the person

### Give Credit

- Always cite sources properly
- Acknowledge original contributors
- Credit improvements and refinements appropriately

### Maintain Quality

- Double-check your mathematics
- Verify citations before submitting
- Test markdown formatting
- Follow the template and guidelines

## Questions?

If you have questions about contributing:

1. Check existing problems for examples
2. Review this guide and the template
3. Open an issue for clarification
4. Tag maintainers in your pull request

## Recognition

All contributors will be acknowledged. Significant contributions (new problems, major updates) will be highlighted in commit messages and pull request descriptions.

Thank you for helping build this resource for the mathematical community!
