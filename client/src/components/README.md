### components

top level components should only contain base components. No business logic, only styling & generic data management (for example, currency input should handle currency logic)

It should be seen mostly as a proxy folder for components built from external dependencies.

Anything related to our business do not belong here. For example, a `recipe-select.component.tsx` does not belong here, as recipe is something we've created to support our use-cases.
