# Copilot Instructions

## Verified project context

- The current site entry point is `index.html`.
- The page is a small, standalone HTML document with CSS in a `<style>` block.
- The current page identifies AD-Digital as an IT solutions company offering web programming and design, Linux software applications, and customized AI agents. Its contact address is `contact@ad-digital.site`.
- Use `website-content.md` as the content reference for verified site copy and content boundaries.
- Do not assume a framework, build system, package manager, backend, API, design system, or additional pages. Inspect the workspace before relying on any of these.

## Working rules

- Treat the existing source files as the source of truth. Read the relevant file and nearby code before editing it.
- Do not invent product requirements, business details, routes, content, assets, dependencies, or runtime behavior. If a required detail is not present, make the smallest reasonable change consistent with the existing site or ask for clarification when the uncertainty materially affects the result.
- Keep changes focused on the request. Preserve existing behavior and the simple static-page structure unless the request explicitly calls for a broader change.
- Reuse existing conventions and dependencies. Do not add a framework or package for a change that can be handled with the current code.
- Make accessibility and responsive behavior part of any page changes; use semantic HTML and retain a working keyboard-accessible experience.
- After editing, run an applicable check already supported by the project. First inspect available scripts and tooling rather than assuming a command exists. If no automated check is available, say what was and was not verified; do not claim tests passed without running them.
- Keep documentation factual. Mark assumptions as assumptions and distinguish observed project behavior from proposed changes.