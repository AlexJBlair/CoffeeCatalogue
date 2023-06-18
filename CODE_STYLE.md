# General style guide

---

## Template

We will attempt to adhere to the following template for all code style guides:

[Angular style guide](https://angular.io/guide/styleguide#angular-coding-style-guide)

## Legend

- Do: Almost alwasys do this.
- Consider: This guideline should generally be followed, but small deviations occur.
- Avoid: Don't do this, bad practice.

---

## General Takeaways

- Try and utilize the "Single responsibility principle" as much as possible.
  - Limit one thing, component or service, to a file. This makes it easier to read, maintain, and test.

---

## Naming Conventions

- Naming is really important and should be consistent.
- Follow pattern for files, symbols as follows:

  - `Feature.type.ts` so for example a test would be `feature.spec.ts` or a service would be feature.service.ts.

- Names should be explicit and not ambiguous. Someone who is new to the project should be able to discern what a piece of code, or a file does, based on the name.
- Separate file names with either dots (.) or dashes (-).
- Avoid abbreviating type in names. Especially for files. So, type out service rather than attempting to abbreviate to serv or svc.
- Classes, Components, Services, Modules, and Pipe names should be PascalCase (aka Upper CamelCase).
- Test spec files should use kebab case and be specific to what is being tested.
- When naming a component selector, use kebab case. (dash - delineated)

---

## File Structure

- Attempt to keep the file structure as flat as possible, as long as possible.

  - However, if it would make sense to create a folder for a feature, do so.

- Keep the file structure consistent. If you create a folder for a feature, keep the file structure the same as other features.

---
