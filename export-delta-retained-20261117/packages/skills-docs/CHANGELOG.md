# @lynx-js/skills-docs

## 0.3.1

### Patch Changes

- Use `pnpx` for one-shot agent-lynx commands in the documentation, bundled skills, and Connector CLI guidance. Use `npm_config_registry` for registry overrides so the examples work on pnpm 10 and 11.
- Updated dependency `@rspress/core` to `2.1.3`.
- Update the Android and Simulator examples to use the client IDs returned by current agent-lynx transports.
- Render reusable agent instructions as copyable Rspress Prompt cards in the getting-started, API docs, and CSS compatibility guides.
- Match interactive examples to the documentation theme, highlight conversation code, and improve the annotated screenshot layout.
- Organize app connections by platform and simplify Getting Started to the four commands for discovering and inspecting a page.
- Keep links between packaged guides on the current site and route links to other Lynx documentation to the corresponding site for each distribution.

## 0.3.0

### Minor Changes

- Remove the A2UI and OpenUI guides from the shared documentation package so the external website can own those pages independently. Thanks [@洪志远](https://export-policy-fixture.byted.org/retained) in [!1054](https://export-policy-fixture.byted.org/retained)

## 0.2.0

No changes in this release.
