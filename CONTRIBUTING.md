# Contributing Guidelines

## What constants are appropriate to record here?

There are of course an infinite number of optimization problems one could pose in mathematics.  To avoid proliferation, one should preferably focus on constants that

- have a significant existing mathematical literature, including incremental improvements on bounds;
- are still actively being researched; and
- are at least somewhat amenable to computational approaches for either upper or lower bounds.

However, exceptions could be made for constants of particular mathematical interest for reasons other than those listed above.

## How to Contribute

### Adding a New Constant

1. **Fork the repository** and create a new branch for your contribution
2. **Create a new file** in the `constants/` directory as `<name>.md`, where `<name>` is some unique name for your constant.
3. **Use the template**: Copy the structure from [template.md](template.md)
4. **Fill in sections**:
   - Provide a clear definition of the constant (call it $C$)
   - Include the current best known bounds with citations
   - Incomplete submissions are welcome; just provide as much information as you have.
5. **Submit a pull request**
6. If approved, I will assign it a number and link to it from the main README.

### Updating Existing Bounds

1. **Fork the repository** and create a new branch
2. **Edit the relevant constant file**:
   - Update the bounds section with new values, with at least one citation or reference
3. **Submit a pull request**
