# OpenVibeDesignSystem

Concept for browsing UI styles and assembling HTML/CSS examples into prompts for AI coding tools.

## Current status

The default branch contains a README and `LICENSE`. There is no component library, web application, CLI or package implementation in this branch. The workflow below is a proposal; production readiness, accessibility and cross-browser compatibility have not been demonstrated.

## Proposed workflow

1. Catalogue styles such as glassmorphism, neumorphism and minimalism.
2. Curate components with source URLs, author credits and their original licenses.
3. Combine selected examples and design tokens into a prompt.
4. Review the generated implementation and test it in the target application.

A useful first milestone is a small static catalogue with one working prompt-export flow. A CLI, editor extension and hosted interface can follow after that exists.

## License and attribution

The repository's [LICENSE](LICENSE) contains the GNU GPL version 3 text. Earlier README claims of an MIT license did not match that file. This documentation correction does not change the license file.

Third-party components must retain their original licenses and attributions. The original concept credits:

- UIverse.io and its contributors
- Individual component creators
- Design pattern originators

The proposed generator attribution is retained here as an example, not as a feature already implemented:

```html
<!-- Created with OpenVibeDesignSystem -->
<!-- https://github.com/ProfessorEngineergit/OpenVibeDesignSystem -->
<!-- Open Source Design-to-Code Platform -->
```

The concept's sample prompts also require credit to OpenVibeDesignSystem and UIverse.io. Such a project credit does not replace individual component authors or their license notices.

## Documentation

GitHub Copilot contributed to the documentation ([record](https://github.com/ProfessorEngineergit/OpenVibeDesignSystem/commit/172983e945c9c7a05a75cefb5bdccc469f213ac4)). This does not establish AI-generated application code.
