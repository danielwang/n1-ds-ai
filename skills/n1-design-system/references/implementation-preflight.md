# Implementation preflight

Read before generating a working interface. This distinguishes an executable implementation from a design-only exercise.

Inspect the actual project for its frontend entry point, manifest/lockfile, installed dependencies, build/test scripts, and existing component imports. Inspect the relevant implementation's API before using it. A Figma property table, generated rendering snippet, or MUI documentation link does not establish an installed code library or a valid application API.

Follow the user's constraints. When an existing stack is required and none is available, request its local path or repository and component package. Do not choose a framework or create substitute components when the user prohibits those choices. Continue independent source comparison, token checks, and a report with the implementation explicitly pending. A mock specification, screenshot, or audit is not a working UI.

If the user permits a new prototype, identify its stack, implementation scope, and local-only product assumptions before building. Do not invent production persistence, authorization, agent capability settings, or endpoints. Preserve a user's existing stack whenever one is provided.

Treat explicit task requirements as active: a request to target WCAG 2.2 AA establishes this task's target even though the bundled N1 policy remains unapproved. Check the applicable standard and actual implementation; do not label that task target optional. Preserve gaps in institutional/global policy separately.

For component selection, distinguish published Figma defaults/options from actual member combinations. `scripts/check_selection.py` can verify original variant names against the bundled members. It does not verify runtime props, approval, or accessibility. Actual code and UI checks must follow when executable artifacts exist.

Report missing inputs precisely. Do not install dependencies for an unchosen framework, generate a fake N1 wrapper, claim a browser/accessibility audit ran without a UI, or imply that a successful package validator proves the interface works.
