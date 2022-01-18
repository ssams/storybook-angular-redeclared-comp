# StorybookRepro

Created with `npx sb@next repro`

Afterwards only the file [src/stories/Button.stories.mdx](src/stories/Button.stories.mdx), which contains
[embedded stories](https://github.com/storybookjs/storybook/blob/6-4-docs/addons/docs/docs/mdx.md#embedding-stories), has been added.

## Triggering the error

Start the storybook via `npm run storybook`. Switching between the individual story pages and the added documentation page triggers
the error:

```
Type ButtonComponent is part of the declarations of 2 modules: StorybookModule and StorybookModule! Please consider moving ButtonComponent to a higher module that imports StorybookModule and StorybookModule. You can also create a new NgModule that exports and includes ButtonComponent then import that NgModule in StorybookModule and StorybookModule.
```